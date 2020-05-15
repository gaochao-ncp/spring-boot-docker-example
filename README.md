# 使用Docker的示例Spring Boot

改编 [Spring Boot 官方指南](https://spring.io/guides/gs/spring-boot-docker/) 以使用 [来自fabric8.io的Docker Maven插件](https://github.com/fabric8io/docker-maven-plugin). 该项目演示了如何对Spring Boot应用程序进行Docker化.

### 需要的版本

所有Maven插件和依赖项都可以从 [Maven中央仓库](https://search.maven.org/)获取. 请安装

* JDK 1.8 
* Maven 3.3+
* Docker 1.13+


### 使用

`mvn clean package -Dmaven.test.skip=true docker:build docker:start`
