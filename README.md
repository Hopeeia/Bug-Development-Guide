# 《程序开发指北》
记录本人开发过程中收获的奇怪教训

## 当你需要 new 一个网络连接

1. 如果你所连接的服务部署在公网、通过域名访问且是自部署或*由其他个人*部署的，出现奇怪的异常请**确保所用域名未过期**且DNS设置正常。

## 当你编译程序时

1. 如果你的程序主要用来发送消息或输出文字，在编译程序前请**确保没有注释掉有用的代码**以免造成刷屏。
