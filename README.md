#spring cloud config demo 简介
spring cloud 子项目，提供分布式配置服务，统一管理集群配置
###依赖库
* Java 8
* Spring Framework 5
* Spring Boot 2
### 依赖项目
* [EurekaServerDemo1(注册中心)](http://localhost:8761/)
  
###项目启动顺序
EurekaServerDemo1,ConfigService,service2,本项目Gateway最后启动

### 启动后项目测试
* 服务刷新，ip方式:http://localhost:8081/actuator/refresh