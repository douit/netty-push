#netty-push

netty主推模式

功能如下：

服务端主动推送消息到客户端

客户端从服务端拉取消息 

客户端和服务端保持长连接 

心跳检测

客户端断线重连（每3秒）


#技术栈

springboot 2.0.4 

netty 4.1.25

fastjson 1.2.47

log4j2