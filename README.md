# springcloud-config-eureka-git
使用Eureka注册中心实现Config的配置服务的高可用
1，去掉spring.cloud.config.uri
2,添加 spring.cloud.config.discovery.ebable=true  开启config服务发现
3，添加 spring.cloud.config.discovery.serviceId=服务端的名称  
3，添加   eureka.client.serviceUrl.defaultZone=http://ip:port/eureka/   注册中心地址
