# spring-boot-thymeleaf

### maven依赖

```xml
		<dependency>
			<groupId>org.springframework.boot</groupId>
			<artifactId>spring-boot-starter-web</artifactId>
		</dependency>
		<dependency>
			<groupId>org.springframework.boot</groupId>
			<artifactId>spring-boot-starter-thymeleaf</artifactId>
		</dependency>
```

### application.properties

```properties
#关闭缓冲
spring.thymeleaf.cache=false  
#前缀（默认为classpath:/templates/）
#spring.thymeleaf.prefix = "classpath:/templates/"
#后缀 （默认为.html）
#spring.thymeleaf.suffix = ".html"
```

### 配置类

```java

ThymeleafProperties{
    
}

```