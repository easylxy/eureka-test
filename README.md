# eureka-test
eureka测试

一个模块多次启动，使用多个application-*.properties

例如：
application-2.properties
application-3.properties
application-4.properties

Run configurations -> Arguments -> Program arguments
分别填入
--spring.profiles.active=2

--spring.profiles.active=3

--spring.profiles.active=4
