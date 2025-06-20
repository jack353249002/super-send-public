SuperSend批量邮件管理工具

SuperSend邮件发送工具是用来通过定义多个smtp协议服务器，通过使用轮询法和协程对多个邮箱号进行并发发送，从而解决单一邮箱服务商免费版本下对用户的发送限制。通过定义imap协议服务器和设置接收规则实现对多个邮箱服务器中的邮件信息聚合展示。

super-send 是邮件发送的核心，主要任务是进行邮件的发送和接收。您可以通过grpc进行远程控制它，具体的proto文件在https://github.com/jack353249002/super-send-public/tree/master/super_send_proto/proto

docker 命令:

    docker push jacksw/super-send:tagname



super-send-tool 是一个用来进行ui可视化管理的工具，主要用来对super-send进行可视化管理。

docker 命令:

    docker push jacksw/super-send-tool:tagname




