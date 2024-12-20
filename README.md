📅 Todo List & Calendar App

💫 소개

Todo List와 Calendar에서 일정을 등록하고 양방향으로 확인할 수 있는 통합 일정 관리 애플리케이션입니다.

배포 서버 URL:  https://todo-front-end-one.vercel.app

📚 API 문서

Swagger UI로 모든 API를 테스트해볼 수 있습니다.

Swagger 사용법 : signUp 요청 -> login 진행 -> 응답 받은 토큰 Bearer 제외하고 토큰값만 최상단 Authorize Value란에 붛혀넣기 후 Authorize 클릭 이후 모든 서비스 이용가능

접속 URL: http://localhost:8080/swagger-ui/index.html

🚀 실행 방법

1️⃣ 프로젝트 클론

원하는 경로에 폴더 생성 후 Git Bash Here 클릭

git init

git clone -b master https://github.com/koreajohn/Todo-BackEnd.git

2️⃣ 프로젝트 설정

VS Code나 IntelliJ 등 선호하는 IDE에서 프로젝트 오픈

src/main 하위경로에 resources 디렉토리 생성 -> 첨부드린 application.properties 파일 붙혀넣기

상단에 File -> Project Structure -> Project SDK: jdk 17 선택 

FIle -> Platform Setting -> SDKs: 17 버전 선택 

Apply -> OK 클릭

상단에 File -> Settings -> Build, Execution, Deployment -> Build Tools -> Gradle 클릭

Gradle JVM jdk 17 버전 선택

Apply -> OK 클릭



3️⃣ DB 스키마 및 기초데이터 등록 및 서버 실행

첨부드린 쿼리 순서대로 실행

어플리케이션 실행 

AssignmentApplication Run 클릭

http://localhost:3000 접속 후 id: admin@naver.com / password: password로 로그인 후 서비스 이용 

🛠️ 기술 스택

🌟 Tech Stack 🌟
<div align="center">
🔙 Backend
<img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white"/>
<img src="https://img.shields.io/badge/Spring-6DB33F?style=flat-square&logo=spring&logoColor=white"/>
<img src="https://img.shields.io/badge/Spring Security-6DB33F?style=flat-square&logo=spring-security&logoColor=white"/>
<img src="https://img.shields.io/badge/JPA-59666C?style=flat-square&logo=hibernate&logoColor=white"/>
<img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white"/>
🎨 Frontend
<img src="https://img.shields.io/badge/React.js-61DAFB?style=flat-square&logo=react&logoColor=black"/>
☁️ DevOps
<img src="https://img.shields.io/badge/AWS EC2-FF9900?style=flat-square&logo=amazon-ec2&logoColor=white"/>
🛠️ Tools
<img src="https://img.shields.io/badge/Swagger-85EA2D?style=flat-square&logo=swagger&logoColor=black"/>
<img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white"/>
</div>
</br>
🔐 Spring Security
<details>
<summary><b>상세 보기</b></summary>
기능

✨ 인증/인가 처리
🔒 JWT 기반 보안
🌐 CORS 관리
⚡ 보안 필터 체인 구성

사용 이유

표준화된 보안 프레임워크 적용
Stateless 서버 아키텍처 구현
안전한 프론트엔드 통신
보안 취약점 최소화

</details>
💾 Spring Data JPA
<details>
<summary><b>상세 보기</b></summary>
기능

🔄 CRUD 자동화
📝 커스텀 쿼리
🔗 엔티티 매핑
💫 트랜잭션 관리

사용 이유

생산성 향상
직관적인 쿼리 생성
데이터베이스 독립성
타입 안전성 보장

</details>
🎯 Jakarta Persistence (JPA)
<details>
<summary><b>상세 보기</b></summary>
기능

🔄 ORM 구현
📊 엔티티 관리
💾 트랜잭션 처리
🔌 DB 연동

사용 이유

객체지향적 DB 처리
높은 생산성과 유지보수성
자동화된 스키마 관리
멀티 DB 플랫폼 지원

</details>
⚡ Lombok
<details>
<summary><b>상세 보기</b></summary>
기능

📝 로깅 기능
🏗️ 생성자 자동화
🔄 Getter/Setter 생성
🎨 빌더 패턴 지원

사용 이유

코드 간소화
가독성 향상
생산성 증대
일관된 코드 관리

</details>
🌐 Spring Web (MVC)
<details>
<summary><b>상세 보기</b></summary>
기능

🔗 REST API 구현
📡 HTTP 처리
🛣️ 라우팅
🏗️ 웹 계층 구성

사용 이유

RESTful 아키텍처 구현
효율적인 프론트엔드 통신
체계적인 요청/응답 처리
확장 가능한 구조

</details>
📚 Swagger
<details>
<summary><b>상세 보기</b></summary>
기능

📝 API 문서화
🧪 테스트 인터페이스
📋 API 스펙 정의

사용 이유

자동화된 문서 관리
통합 테스트 환경
원활한 협업
실시간 API 관리

</details>
🔄 Jackson
<details>
<summary><b>상세 보기</b></summary>
기능

🔄 JSON 처리
🔃 객체 변환
📊 데이터 포맷팅

사용 이유

효율적인 데이터 변환
RESTful 데이터 처리
다양한 타입 지원
커스텀 규칙 적용

</details>
🎯 프로젝트 목표

📈 개발 생산성 향상
🎨 코드 품질과 유지보수성 확보
🔒 보안성 강화
🏗️ 확장 가능한 아키텍처 구현
👥 효율적인 협업 환경 구축


<div align="center">
© 2024 Todo List & Calendar App - Developed with ❤️ by koreajohn
</div>
