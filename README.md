# tcpSocketClientDemo

###一个使用tcp socket和服务器互发消息的demo
####原始代码来源于这篇[博客](http://www.jianshu.com/p/cc756016243b "")，我在其基础上添加以下功能和说明如下：
1.原代码使用同步等待，客户端发消息后界面被卡死。增加一个线程，将其改成异步，界面流畅可任意发消息。

2.线程使用runloop技术使其在后台始终保持不退出，就像AFNetworking的单例一样

3.使用timer模拟服务器接收消息，这是一个demo并未处理各种异常

![][https://github.com/sidetlw/tcpSocketClientDemo/blob/master/CSSocketDemo/shot/Untitled.gif]
