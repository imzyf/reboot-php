# 网络协议

## 考点

- HTTP 协议状态码
- OSI 七层模型
- HTTP 协议的工作特点和工作原理
- HTTP 协议常见请求、响应头和请求方法
- HTTPS 工作原理
- 常见网络协议含义及端口

## HTTP 协议状态码

### 1xx

信息类

### 2xx

成功

- 200 ok
- 201 create success
- 204 已经成功处理 不含 content，delete success
- 206 部分内容处理

### 3xx

重定向，需要额外操作

- 301 永久性重定向
- 302 临时重定向
- 303 See Other 自 RFC 2616 (HTTP 1.1)起，用于在收到 HTTP POST 请求之后，进行 URL 重定向的操作。
- 304 Not Modified 无需再次传输请求的内容，可以使用缓存的内容

### 4xx

客户端错误

- 400 请求报文语法错误
- 401 缺少认证信息
- 403 服务器拒绝
- 404 资源不存在

### 5xx

服务端错误，处理请求错误

- 501 Not Implemented 请求的方法不被服务器支持
- 503 Service Unavailable 由于服务器停机维护或者已超载

## OSI 七层模型

## HTTP 协议的工作特点和工作原理

- B/S 模式
- 通信开销小、简单快速、传输成本低
- 使用灵活、可使用超文本传输协议
- 节省传输时间
- 无状态

工作原理

## HTTP 协议常见请求、响应头和请求方法

- Content-Type
- Accept
- Origin
