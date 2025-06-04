# 📦 Spring Cloud Eureka 기반 MSA 프로젝트

본 저장소는 Spring Cloud Netflix Eureka를 활용한 MSA(Microservice Architecture) 예제 프로젝트입니다.  
서비스 등록/탐색, API Gateway 연동 등 분산 시스템 아키텍처 구성에 필요한 핵심 요소들을 포함하고 있습니다.

## 🧩 프로젝트 구성

- `discovery-service`: Eureka Server
- `api-gateway-service`: Spring Cloud Gateway
- `user-service`: 회원 마이크로서비스 예제
- `order-service`: 주문 마이크로서비스 예제

## 🛠 사용 기술

- Java, Spring Boot, Spring Cloud (Eureka, Gateway)
- Gradle, Docker
- AWS, Azure, Redis 등 클라우드 인프라 연동 가능

## 🚀 실행 방법

1. `discovery-service` 실행 (Eureka 서버)
2. `user-service`, `order-service` 실행 (각 서비스)
3. `api-gateway-service` 실행 (Gateway)
4. [http://localhost:8761](http://localhost:8761) 에서 서비스 등록 상태 확인

## 🌐 API 예시

GET http://localhost:8080/user-service/users
GET http://localhost:8080/order-service/orders

## 📌 활용 목적

- MSA 아키텍처 학습
- 클라우드 이전 테스트
- 사내 서비스 분산 구조 시뮬레이션

## 🙋‍♂️ About Me

신용철 (Yongchul Shin)  
전 서든어택 프로게이머 → 백엔드 개발자  
GitHub: github.com/yongchulShin  
Email: prozernim@gmail.com  
