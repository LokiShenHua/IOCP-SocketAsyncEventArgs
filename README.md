# IOCP-SocketAsyncEventArgs
C#高性能大容量SOCKET并发完成端口例子（有C#客户端）    例子主要包括SocketAsyncEventArgs通讯封装、服务端实现日志查看、SCOKET列表、上传、下载、远程文件流、吞吐量协议，用于测试SocketAsyncEventArgs的性能和压力，最大连接数支持65535个长连接，最高命令交互速度达到250MB/S（使用的是127.0.0.1的方式，相当于千兆网卡1Gb=125MB/S两倍的吞吐量）。服务端用C#编写，并使用log4net作为日志模块；  同时支持65536个连接，网络吞吐量可以达到400M。
