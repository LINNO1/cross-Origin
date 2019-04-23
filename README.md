# cross-Origin
跨域通信

1. 修改host: 
   添加 
   ```
127.0.0.1 a.com
127.0.0.1 b.com
127.0.0.1 a.test.com
127.0.0.1 b.test.com
   ``` 
2. node server.js 启动服务器
3. 浏览器localhost:a.com:8080/zhubao.html 测试JSONP 和 CORS 跨域通信
4  浏览器localhost:a.test.com:8080/zhubao.html 测试多级页面下,用 document.domain 和window.postMessage跨域通信
