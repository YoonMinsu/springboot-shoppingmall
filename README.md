# :shopping_cart: 스프링 부트로 만드는 쇼핑몰 프로젝트

## :link: 배포 URL
* http://fancy-cart.ga

## :clipboard: 개발환경
* IntelliJ
* Postman
* HeidiSql
* Sourcetree
* GitHub

## :clipboard: 성능 테스팅 도구
* K6
* Grafana
* InfluxDB

## :clipboard: 로그 분석 도구
* ELK Stack
  * Elasticsearch, Logstash, Kibana, Filebeats

## :clipboard: 사용 기술
### 백엔드
#### Spring boot
* JAVA 8
* Spring MVC
* Spring Boot Security
* Spring Boot Actuator
* Spring Data JPA
* Spring Boot Batch
* Spring AOP

#### Build tool
* Gradle

#### Database
* Mysql
* Redis

#### AWS
* EC2
* S3

#### Message Queue
* Kafka

#### CI
* Travis CI

### 프론트엔드
* Javascript
* Thymeleaf
* jQuery

## :clipboard: 주요 키워드
* REST API
* 시큐리티
* 배치
* 스케줄링
* HTTP 통신
* JPA
* 페이징
* 트랜잭션
* 예외처리
* Git 버전관리
* AWS EC2 배포
* Message Queue
* Event Driven Architecture

## :factory: 시스템 구조
<img width="1000" alt="캡처7" src="https://user-images.githubusercontent.com/40568894/98373057-09f7bc80-2082-11eb-8b6f-70f927287099.PNG"><img width="1000" alt="캡처8" src="https://user-images.githubusercontent.com/40568894/98373737-09abf100-2083-11eb-9577-6990efefcc76.PNG">

## :link: quartz 배치
* [quartz-batch 스케줄러](https://github.com/didrlgus/springboot-shoppingmall/tree/master/app/batch-server)

## :link: mail 서버 (Consumer)
* [mail 서버](https://github.com/didrlgus/springboot-shoppingmall/tree/master/app/mail-server)

## :link: redis update 권한 서버
* [redis update 권한 서버 Repository](https://github.com/didrlgus/redis-update-server)

## :link: Trouble Shooting
* [API 성능 테스트 에서 발생한 문제 해결을 위한 시도](https://github.com/didrlgus/springboot-shoppingmall/issues/6)

## :link: 성능 테스트
* [초기 성능 테스트 결과](https://github.com/didrlgus/springboot-shoppingmall/issues/5)
* [메인화면 API 캐시 적용 전, 후 성능 테스트 비교 결과](https://github.com/didrlgus/springboot-shoppingmall/issues/21)

## :link: ERD 설계
* [shopping mall ERD](https://github.com/didrlgus/springboot-shoppingmall/issues/1)

## Rest API 설계
![REST API1](https://user-images.githubusercontent.com/40568894/64402718-d3569880-d0b0-11e9-90df-e14b1a5389bd.png)
![REST API2](https://user-images.githubusercontent.com/40568894/64402722-d6518900-d0b0-11e9-90d3-6a31dbd4f0dd.png)
![REST API3](https://user-images.githubusercontent.com/40568894/64402726-d8b3e300-d0b0-11e9-863f-8f654f3df4d6.png)
![REST API4](https://user-images.githubusercontent.com/40568894/64402728-d9e51000-d0b0-11e9-895f-450f3dae64db.png)
