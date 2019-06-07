# eureka-discovery

This is a pretty simple spring boot service making use of the @EnableEurekaServer annotation. 

Eureka should be available at http://localhost:8761/ (Check application.properties to see if port has changed)

@EnableEurekaServer annotation is available by adding the dependency 
<dependency>
            <groupId>org.springframework.cloud</groupId>
            <artifactId>spring-cloud-starter-netflix-eureka-server</artifactId>
            <version>1.4.7.RELEASE</version>
</dependency>
        
