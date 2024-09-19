# Spring Boot 기술 모음 리포지토리 🌱

[![My Skills](https://skillicons.dev/icons?i=java,gradle,spring&theme=dark)](https://skillicons.dev)


Spring Boot 프로젝트에서 사용되는 다양한 기술과 설정을 모아둔 **Spring Boot 기술 모음** 리포지토리에 오신 것을 환영합니다!  
이 리포지토리는 개발의 효율성을 높이고 성능을 강화하기 위해 제가 사용한 여러 기술들을 정리한 공간입니다. 아래에서 사용된 주요 기술들과 몇 가지 예시들을 확인하실 수 있습니다.

## 🔧 사용된 기술

| 기술      | 설명                                                           |
|-----------|----------------------------------------------------------------|
| **SPRING**| Java 기반 웹 애플리케이션을 구축하기 위한 핵심 프레임워크입니다.   |
| **JPA**   | Java 애플리케이션에서 관계형 데이터를 관리하기 위한 표준 API입니다. |
| **CACHE** | 자주 사용하는 데이터를 캐싱하여 지연 시간을 줄이고 성능을 향상시킵니다. |
| **TOML**  | 읽기 쉬운 간단한 구성 파일 형식으로, 유연하고 가독성이 높습니다.     |

---

## 🚀 주요 기능

- **Spring 프레임워크**를 사용한 확장 가능한 웹 애플리케이션 개발.
- **JPA 통합**을 통한 데이터베이스 관리의 간소화.
- **캐시 메커니즘**을 사용하여 애플리케이션 성능 향상.
- **TOML 구성 예시**로 가벼운 구성 파일 형식을 보여줍니다.

---

## 📂 프로젝트 구조

리포지토리는 쉽게 탐색할 수 있도록 폴더로 정리되어 있습니다:
- `/spring-configs` — Spring 프레임워크 설정 파일들.
- `/jpa-configs` — JPA 및 영속성 관련 파일들.
- `/cache-configs` — 캐시 설정과 예시들.
- `/toml-examples` — TOML을 사용한 구성 예시 파일들.

---

## 📝 TOML: 새로운 추가 사항

**TOML (Tom's Obvious, Minimal Language)** 은 간단하고 사람이 읽기 쉬운 구성 파일 형식입니다.   
TOML은 구조가 명확하여 Spring Boot 프로젝트에서 설정 파일로 사용하기에 이상적입니다. 다음은 TOML 파일 구성 예시입니다:

```toml
[versions]
java = "17"
springboot-version = "3.3.3"

[libraries]
spring-boot-starter-web = { module = "org.springframework.boot:spring-boot-starter-web", version.ref = "springboot-version" }

[plugins]
spring-boot = { id = "org.springframework.boot", version.ref = "springboot-version" }
spring-dependency-management = { id = "io.spring.dependency-management", version = "1.1.6" }
```