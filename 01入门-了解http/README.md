## Http
      请求报文
          请求头：请求头包含了很多键值对
              Cookie:  key: value形式 
                  Cookie由服务端或者后端产生，交给客户端，浏览器端。在客户端进行保存。
                  客户端在下次发送请求时会带上对应的Cookie
              Content-Type: 声明请求报文当中 请求体数据格式
                  application/x-www-form-urlencoded  -> username=tom&pwd=123
                  application/json  ->  {"username": "tom","pwd": 123}

      响应报文： 
          响应头： 
              Content-Type: 描述了响应体当中返回的数据格式,编码格式
                  text/html;charset=utf-8
                  text/json;
              Set-Cookie: 键值对
                  服务端通过Set-Cookie设置Cookie并且传递给客户端

### API分类
      REST API： 
          同一个请求路径可以进行多种操作
          请求方式会用到GRT/POST/PUT/DELETE
      非 REST API
          一个请求只对应一个操作
          一般只有GET/POST