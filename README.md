#  Microservices, Spring Cloud, Spring Boot, React, MySQL, Hibernate, Liquibase

The application structure is as follows.
- **microservice-user-management** - Microservice implemented using Spring boot. [More info](microservice-user-management/README.md)
- **microservice-course-management** - Microservice implemented using Spring boot. [More info](microservice-course-management/README.md)
- **eureka-discovery-service** - Microservice implemented using Spring eureka. [More info](eureka-discovery-service/README.md)
- **zuul-gateway-service** - Microservice implemented using Spring zuul. [More info](zuul-gateway-service/README.md)

### Build

#### 1) Build Spring Boot microservices
   
```
$ cd microservice path
$ gradlew bootJar
$ gradlew bootRun
```


