# gb28281 Server
`sip服务器` 和 运行`nginx-rtmp`模块进行推流  
`sip服务器模块`负责与摄像机，客户端交互 主要负责转发客户端请求和控制命令 和保持与摄像机的心跳  
`rtp模块`负责将`ps`流 解析为`h264`码流 并封装发送到`nginx`服务器 进行`rtmp`推流  
