# Oracle Helidon

Oracle Helidon은 Eclipse Foundation의 MicroProfile을 구현한 마이크로 서비스 개발 프레임웍 입니다.  
본 레파지토리에서는 다양한 Oracle Helidon 예제들을 제공합니다.

***

### Helidon 공식 홈페이지
https://helidon.io

### Helidon 공식 가이드
https://helidon.io/docs/latest

### Prerequisites
#### 데스크탑 설치 프로그램
* [Java SE 8 or Open JDK 8](http://jdk.java.net/)
* [Maven 3.5](https://maven.apache.org/download.cgi)

### Quickstart
Helidon Maven archetypes로 Helidon 프로젝트 소스를 생성할 수 있습니다.  
archetypeArtifactId는 Helidon SE와 Helidon MP로 나눠서 제공됩니다.  

#### Quickstart Helidon SE
```
mvn archetype:generate -DinteractiveMode=false -DarchetypeGroupId=io.helidon.archetypes -DarchetypeArtifactId=helidon-quickstart-se -DarchetypeVersion=1.0.2 -DgroupId=io.helidon.examples -DartifactId=helidon-quickstart-se -Dpackage=io.helidon.examples.quickstart.se
```

#### Quickstart Helidon MP
```
mvn archetype:generate -DinteractiveMode=false -DarchetypeGroupId=io.helidon.archetypes -DarchetypeArtifactId=helidon-quickstart-mp -DarchetypeVersion=1.0.2 -DgroupId=io.helidon.examples -DartifactId=helidon-quickstart-mp -Dpackage=io.helidon.examples.quickstart.mp
```