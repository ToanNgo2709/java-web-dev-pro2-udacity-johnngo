# Boogle Maps

This is Eureka Server

## Instructions

Via shell it can be started using

```
$ mvn clean package
```

If any issue related to no main manifest, use this in project
```
$ mvn package spring-boot:repackage
```

```
$ java -jar target/eureka-server-0.0.1-SNAPSHOT.jar
```

The service is available by default on port `8171`. You can check it on the 
command line by using


You can also import it as a Maven project on your preferred IDE and 
run the class `EurekaServerApplication`.