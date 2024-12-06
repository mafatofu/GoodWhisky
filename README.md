# Good Whisky

### 사용자가 원하는 위스키를 찾아주는 챗봇 어플리케이션

- 사용자가 특정 문장으로 검색 시 사용자에게 위스키를 추천해준다.
    - 달달한 위스키를 추천해줘
    - 연말 파티에 어울리는 위스키를 알려줘

### 프로젝트 기간

- 2024.12.06~2024.01.06

### 기술 스택

**[Backend]**

- Java 17, Springboot, Spring security, Jpa, Jwt, Oauth2

**[Frontend]**

- React

**[DB]**

- Redis

**[Etc]**

Github, Github Actions, Docker, Aws

### IDE

- intelliJ ultimate 24.03 ver

### Framework

- springboot 3.3.6

### ERD

- 

### 화면 기획

### 구조도

### API 명세

### 기능 설명

### dependency

```java
dependencies {

  //JWT
  implementation 'io.jsonwebtoken:jjwt-api:0.12.5'
  runtimeOnly 'io.jsonwebtoken:jjwt-impl:0.12.5'
  runtimeOnly 'io.jsonwebtoken:jjwt-jackson:0.12.5'
  //jpa
  implementation 'org.springframework.boot:spring-boot-starter-data-jpa'
  //redis
  implementation 'org.springframework.boot:spring-boot-starter-data-redis'
  implementation 'org.springframework.boot:spring-boot-starter-data-redis-reactive'
  implementation 'org.springframework.ai:spring-ai-redis-store-spring-boot-starter'
  //mail
  implementation 'org.springframework.boot:spring-boot-starter-mail'
  //oauth2
  implementation 'org.springframework.boot:spring-boot-starter-oauth2-client'
  //security
  implementation 'org.springframework.boot:spring-boot-starter-security'
  //thymeleaf
  implementation 'org.springframework.boot:spring-boot-starter-thymeleaf'
  //web
  implementation 'org.springframework.boot:spring-boot-starter-web'
  //spring ai
  implementation platform("org.springframework.ai:spring-ai-bom:1.0.0-SNAPSHOT")
  //openai
  implementation 'org.springframework.ai:spring-ai-openai-spring-boot-starter'
  //spring security
  implementation 'org.thymeleaf.extras:thymeleaf-extras-springsecurity6'
  //lombok
  compileOnly 'org.projectlombok:lombok'
  annotationProcessor 'org.projectlombok:lombok'
  //devtools
  developmentOnly 'org.springframework.boot:spring-boot-devtools'
  //mysql
  runtimeOnly 'com.mysql:mysql-connector-j'
  //test
  testImplementation 'org.springframework.boot:spring-boot-starter-test'
  testImplementation 'io.projectreactor:reactor-test'
  testImplementation 'org.springframework.security:spring-security-test'
  testRuntimeOnly 'org.junit.platform:junit-platform-launcher'
  //H2
  runtimeOnly 'com.h2database:h2'

}
```

## 실제 동작 화면
