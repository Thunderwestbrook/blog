到现在为止，HTTP协议已经有三个版本了
- HTTP1.0
- HTTP1.1
- HTTP/2

#### HTTP1.0
- HTTP1.0默认是短链接(每次与服务器交互，都需要新开一个连接)
- 在HTTP1.0中，发送一次请求时，需要等待服务端响应了才可以继续发送请求。

#### HTTP1.1
- HTTP1.1是持久化链接(建立一次连接，多次请求均由这个连接完成)
- 在HTTP1.1中，发送一次请求时，不需要等待服务端响应了就可以发送请求了，但是回送数据给客户端的时候，客户端还是需要按照响应的顺序来一一接收

#### HTTP/2
HTTP2与HTTP1.1最重要的区别就是解决了线头阻塞的问题