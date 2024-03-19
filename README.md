# Getting Started


### Project Purpose

* RabbitMQ를 활용한 메시지 큐 구현
* TDD 방식으로 개발 연습
* 하나의 프로젝트에서 dockerize를 통한 RabbitMQ 서버와 Spring Boot 서버를 연동하여 테스트
* Database에 ORDER와 TASKSTATUS 테이블 정보를 저장
* Refactoring 및 Clean Code 작성


### 개발 테스트 환경

* Java 17
* Spring Boot 3.2.3
* RabbitMQ
* Docker
* PostgreSQL


### Guides

#### How to run the application
```angular2html
./gradlew clean build

docker-compose up --build
```


#### API Endpoints

```
POST "/api/order"

```


### Reference Links

* [RabbitMQ](https://www.rabbitmq.com/)
* [ChatGPT](https://chat.openai.com/)
