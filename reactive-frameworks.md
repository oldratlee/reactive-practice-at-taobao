# 常见Reactive库及其之间的联系

1. Reactive Streams(即Java9 Flow API)  
    Reactive的核心设计思路和底层模式，提供的了RS的API（4个接口）及规范（这个接口及其之间的实现契约）。  
    http://www.reactive-streams.org/ | https://github.com/reactive-streams/reactive-streams-jvm
1. ReactiveX（Reactive扩展） / RxJava  
    依赖Reactive Streams，提供扩展，如使用方式和工具实现，RxJava本身没有网络集成  
    http://reactivex.io/ | https://github.com/ReactiveX/RxJava
1. VertX  
    消息和non-blocking的框架，提供Http、JDBC/Mongo/Redis、RxJava、服务发现等支持。  
    http://vertx.io/ | https://github.com/eclipse/vert.x | https://github.com/vert-x3/vertx-examples
1. Akka  
    Actor模式/架构，基于消息，提供网络、集群、路由、服务发现等支持。  
    https://akka.io/ | https://github.com/akka/akka
