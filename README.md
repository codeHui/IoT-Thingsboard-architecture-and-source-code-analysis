对IoT服务器设计感兴趣的欢迎先Star支持🐵，长期更新与维护。该blog不只是Thingsboard，Thingsboard的文章中也会包含很多IoT服务器通用设计的想法和思考。


## IoT服务器通用架构与设计
* [**Thingsboard微服务分布式下-设备控制的数据流-架构与可用性分析（有架构图）**](https://github.com/codeHui/IoT-Thingsboard-architecture-and-source-code-analysis/wiki/Thingsboard%E5%BE%AE%E6%9C%8D%E5%8A%A1-%E5%88%86%E5%B8%83%E5%BC%8F-%E8%AE%BE%E5%A4%87%E6%8E%A7%E5%88%B6%E7%9A%84%E6%95%B0%E6%8D%AE%E6%B5%81-%E6%9E%B6%E6%9E%84%E4%B8%8E%E5%8F%AF%E7%94%A8%E6%80%A7%E5%88%86%E6%9E%90)  

* [**高并发下，IoT异步（queue或mqtt）转同步（http）的java代码实现**](https://github.com/codeHui/IoT-Thingsboard-architecture-and-source-code-analysis/wiki/%E9%AB%98%E5%B9%B6%E5%8F%91%E4%B8%8B%EF%BC%8C%EF%BC%88IoT%EF%BC%89%E5%BC%82%E6%AD%A5%EF%BC%88%E5%A6%82queue%E3%80%81mqtt%EF%BC%89%E8%BD%AC%E5%90%8C%E6%AD%A5%EF%BC%88%E5%A6%82http%EF%BC%89%E7%9A%84java%E4%BB%A3%E7%A0%81%E5%AE%9E%E7%8E%B0)  

* thingsboard actor源码分析（待更新）
* thingsboard 规则引擎实现分析（待更新）
* [Thingsboard 图表时序数据统计-部分源码简单分析](https://github.com/codeHui/IoT-Thingsboard-architecture-and-source-code-analysis/wiki/Thingsboard-%E5%9B%BE%E8%A1%A8%E6%95%B0%E6%8D%AE%E7%BB%9F%E8%AE%A1%E9%83%A8%E5%88%86%E6%BA%90%E7%A0%81%E7%AE%80%E5%8D%95%E5%B1%95%E7%A4%BA)

## Thingsboard 部分源码或设计
* [消息队列 kafka topic 设计](https://github.com/codeHui/IoT-Thingsboard-architecture-and-source-code-analysis/wiki/Thingsboard-%E6%B6%88%E6%81%AF%E9%98%9F%E5%88%97-kafka-topic-%E8%AE%BE%E8%AE%A1)  
* [Thingsboard Netty Mqtt 实现](https://github.com/codeHui/IoT-Thingsboard-architecture-and-source-code-analysis/wiki/Thingsboard-Netty-Mqtt-%E5%AE%9E%E7%8E%B0%E5%88%86%E6%9E%90)
* [在Thingboard如何打印mqtt入口日志](https://github.com/codeHui/IoT-Thingsboard-architecture-and-source-code-analysis/wiki/%E5%9C%A8Thingboard%E5%A6%82%E4%BD%95%E6%89%93%E5%8D%B0mqtt%E5%85%A5%E5%8F%A3%E6%97%A5%E5%BF%97)

## Thingsboard 二次开发方案
* [Thingsboard 实现黑暗模式 Dark Mode](https://github.com/codeHui/IoT-Thingsboard-architecture-and-source-code-analysis/wiki/Thingsboard-%E5%AE%9E%E7%8E%B0%E9%BB%91%E6%9A%97%E6%A8%A1%E5%BC%8F-Dark-Mode)    
* [Thingsboard V3.9 前端二次开发创建新的菜单页面](https://github.com/codeHui/IoT-Thingsboard-architecture-and-source-code-analysis/wiki/Thingsboard-V3.9--%E5%89%8D%E7%AB%AF%E4%BA%8C%E6%AC%A1%E5%BC%80%E5%8F%91%E5%88%9B%E5%BB%BA%E6%96%B0%E7%9A%84%E8%8F%9C%E5%8D%95%E9%A1%B5%E9%9D%A2)
* [基于iframe页面嵌套的Thingsboard二次开发方案](https://github.com/codeHui/IoT-Thingsboard-architecture-and-source-code-analysis/wiki/%E5%9F%BA%E4%BA%8Eiframe%E9%A1%B5%E9%9D%A2%E5%B5%8C%E5%A5%97%E7%9A%84Thingsboard%E4%BA%8C%E6%AC%A1%E5%BC%80%E5%8F%91%E6%96%B9%E6%A1%88)
* [Thingsboard单体部署Docker去除内置PostgreSQL(使用外部PostgreSQL)](https://github.com/codeHui/IoT-Thingsboard-architecture-and-source-code-analysis/wiki/Thingsboard%E5%8D%95%E4%BD%93%E9%83%A8%E7%BD%B2Docker%E5%8E%BB%E9%99%A4%E5%86%85%E7%BD%AEPostgreSQL(%E4%BD%BF%E7%94%A8%E5%A4%96%E9%83%A8PostgreSQL))  
* [利用Thingsboard规则引擎（或Kafka流计算），根据电表上报的累计总电量，生成每天的耗电量统计](https://github.com/codeHui/IoT-Thingsboard-architecture-and-source-code-analysis/wiki/%E5%88%A9%E7%94%A8Thingsboard%E8%A7%84%E5%88%99%E5%BC%95%E6%93%8E%EF%BC%88%E6%88%96Kafka%E6%B5%81%E8%AE%A1%E7%AE%97%EF%BC%89%EF%BC%8C%E6%A0%B9%E6%8D%AE%E7%94%B5%E8%A1%A8%E4%B8%8A%E6%8A%A5%E7%9A%84%E7%B4%AF%E8%AE%A1%E6%80%BB%E7%94%B5%E9%87%8F%EF%BC%8C%E7%94%9F%E6%88%90%E6%AF%8F%E5%A4%A9%E7%9A%84%E8%80%97%E7%94%B5%E9%87%8F%E7%BB%9F%E8%AE%A1)
* [Thingsboard SCADA, 工业物联网SCADA监控web版, 数字孪生Digital Twin](https://github.com/codeHui/IoT-Thingsboard-architecture-and-source-code-analysis/wiki/Thingsboard-SCADA,-%E5%B7%A5%E4%B8%9A%E7%89%A9%E8%81%94%E7%BD%91SCADA%E7%9B%91%E6%8E%A7web%E7%89%88,-%E6%95%B0%E5%AD%97%E5%AD%AA%E7%94%9FDigital-Twin)  
* [外部博客链接](https://github.com/codeHui/IoT-Thingsboard-architecture-and-source-code-analysis/wiki/%E5%A4%96%E9%83%A8%E5%8D%9A%E5%AE%A2%E9%93%BE%E6%8E%A5)

## Thingsboard 收费版
* [ThingsBoard Professional Edition (收费版) 配置经验](https://github.com/codeHui/IoT-Thingsboard-architecture-and-source-code-analysis/wiki/ThingsBoard-Professional-Edition%E9%85%8D%E7%BD%AE%E7%BB%8F%E9%AA%8C) 
  
[欢迎讨论区留言](https://github.com/codeHui/IoT-Thingsboard-architecture-and-source-code-analysis/discussions)
