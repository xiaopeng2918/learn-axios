### delete put get post请求
      delete 
          请求拼接params参数
      put
          请求拼接params参数
          请求体还要传输data数据
      get
          请求可以传query参数
        注意： 在axios中请求配置对象params属性对应的是query参数
      post
          请求体传输data数据

**注意：**在请求体当中发送数据时，需要设置请求体数据类型
              Content-Type: application/json -> JSON.parse(js对象)
              Content-Type: application/xxx-form-urlencoded -> ?xx=xxx&xx=xxx