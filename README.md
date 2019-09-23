Add dependencies to pom.xml

```xml
        <!-- Spring boot actuator to expose metrics endpoint -->
        <dependency>
            <groupId>org.springframework.boot</groupId>
            <artifactId>spring-boot-starter-actuator</artifactId>
        </dependency>
        <!-- Micrometer Prometheus registry  -->
        <dependency>
            <groupId>io.micrometer</groupId>
            <artifactId>micrometer-registry-prometheus</artifactId>
        </dependency>
```

Spring Boot Actuator 
http://localhost:8080/actuator/

Timeseries monitoring in Prometheus pattern
http://localhost:8080/actuator/prometheus

