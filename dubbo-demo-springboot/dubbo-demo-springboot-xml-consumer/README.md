# dubbo-demo-springboot-xml-consumer
此服务模块是由springboot、dubbo、curator-recipes等主要组件构成，演示springboot结合dubbo的xml方式订阅服务的过程,是dubbo服务的消费者。
    
## 备注
* 启动服务时，注意一下zookeeper服务的版本号与curator-recipes版本号是否对应；
* 此服务模块应用assembly插件来规范服务打包的目录结构，具体可参考：https://github.com/yifei-2018/multi-environment;