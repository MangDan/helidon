
# Helidon Example: helidon-hikaricp

본 예제는 Helidon 에서 Hikari Connection Pool을 사용해서 Oracle Database와 연결하여 간단한 쿼리를 실행하고,  
결과를 JSON으로 리턴하는 예제입니다.

## You have to add below to pom.xml
```xml
<dependency>
    <groupId>io.helidon.integrations.cdi</groupId>
    <artifactId>helidon-integrations-cdi-datasource-hikaricp</artifactId>
</dependency>
<dependency>
    <groupId>com.oracle</groupId>
    <artifactId>ojdbc6</artifactId>
    <version>11.2.0.4</version>
</dependency>
```

## Move to project directory and Build

```
cd helidon-hikaricp

mvn package
```

## Start the application

```
java -jar target/helidon-hikaricp.jar
```

## Exercise the application

```
curl -X GET http://localhost:8080/books
```