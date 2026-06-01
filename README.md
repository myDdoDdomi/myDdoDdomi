<div align="center">
  <h1>💻 Backend Engineer</h1>
  <h3>Complexity to Clarity — 확장 가능한 백엔드 설계와 실전 구현</h3>
  <p>
    복잡한 요구사항을 분석해 <strong>안정적이고 확장 가능한 서버 아키텍처</strong>를 설계하고,<br>
    <strong>AI 모델 연동과 데이터 파이프라인</strong>을 통해 서비스 가치를 만드는 백엔드 개발자입니다.
  </p>

  <br>

  <!-- Languages -->
  <img src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=java&logoColor=white">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white">
  <img src="https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white">
  <img src="https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black">
  <br>

  <!-- Backend / Frameworks -->
  <img src="https://img.shields.io/badge/Spring Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white">
  <img src="https://img.shields.io/badge/Spring Security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white">
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white">
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white">
  <br>

  <!-- Data -->
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white">
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white">
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white">
  <br>

  <!-- Infra / Cloud -->
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white">
  <img src="https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white">
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white">
  <img src="https://img.shields.io/badge/Firebase-DD2C00?style=for-the-badge&logo=firebase&logoColor=white">
  <img src="https://img.shields.io/badge/Google Cloud-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white">
  <br>

  <!-- AI -->
  <img src="https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white">
  <img src="https://img.shields.io/badge/HuggingFace-FF6F00?style=for-the-badge&logo=huggingface&logoColor=white">
  <img src="https://img.shields.io/badge/YOLO-00FFFF?style=for-the-badge&logo=yolo&logoColor=black">
</div>

<br>

## 💡 Professional Summary
* **Full-Cycle Engineering** — 요구사항 분석부터 아키텍처 설계, 구현, Docker/Jenkins 기반 CI/CD 배포까지 프로젝트 전 과정을 경험했습니다.
* **Backend & AI Integration** — Spring Boot(Java)와 FastAPI(Python)를 분리한 이중 서버 구조에서 AI 모델 서빙을 연동하고, Redis 캐싱·비동기 처리·쿼리 개선으로 성능을 개선했습니다.
* **Team Leadership** — 3개 핵심 프로젝트의 팀장과 SSAFY 실습 코치 경험을 바탕으로 기술적 의사결정과 협업을 이끌었습니다.

---

## 🚀 Key Projects

### 1️⃣ Happy:Re — AI 감정분석 심리 케어 플랫폼
> 일기 텍스트의 감정을 AI로 분석·시각화하고, 익명 음성채팅으로 감정을 나누는 웹 서비스

**Role** · 팀장, Backend & AI Serving
**Stack** · `Spring Boot` `FastAPI` `HuggingFace` `MySQL` `Redis` `WebRTC` `OpenAI API` `Docker` `Jenkins`

- 데이터셋 재정의와 파이프라인 개선으로 감정 분류 모델의 분류 품질을 향상
- AI 추론 서버(FastAPI)를 별도 서비스로 분리해 유연한 모델 서빙 구조 확립
- Redis 캐싱 전략을 도입해 반복 조회 응답성을 개선
- WebRTC 기반 실시간 익명 음성채팅 구현
- 🔗 https://github.com/myDdoDdomi/Happy-RE_russel_ai

---

### 2️⃣ AllEat — AI 식단/식비 자동화 솔루션
> 객체 탐지(Object Detection)로 사진 한 장으로 식단을 기록하고 식비를 자동 분석하는 서비스

**Role** · 팀장, Backend & AI Integration, API Design
**Stack** · `Spring Boot` `Spring Security/JWT` `OAuth2.0` `JPA` `MySQL` `FastAPI` `YOLOv10` `React Native` `Docker` `Jenkins` `AWS EC2`

- 사진 기반 원터치 입력으로 식단 기록 단계를 대폭 단축
- YOLOv10 식단 인식 추론 서버와 Spring Boot 비즈니스 서버를 연동한 이중 서버 구조 설계
- 거래내역·식단·영양 도메인을 정규화 설계하고 JPA로 매핑, 조회 시 N+1을 고려한 Fetch 전략 적용
- 대용량 이미지 업로드 비동기 처리 및 RESTful API 표준 수립
- 🔗 https://github.com/myDdoDdomi/AllEat_pjt

---

### 3️⃣ PushOfLife — WearOS 응급상황 자동 탐지 시스템
> 스마트워치 센서로 응급상황을 감지하고 주변 헬퍼에게 실시간 구조 요청·CPR 가이드를 제공

**Role** · 팀장, WearOS 개발 (백엔드 위치검색 로직 공동 구현)
**Stack** · `Spring Boot` `Kotlin (WearOS)` `Redis (Geospatial)` `MongoDB` `FCM`

- 갤럭시 워치 센서(가속도·심박) 기반 이상 징후 감지 및 자동 알림 흐름 설계
- 반경 내 헬퍼 탐색을 전체 탐색에서 **Redis Geospatial 인덱스 기반(로그 시간) 검색**으로 개선 — 팀과 공동 설계·구현
- BLE 연결 기반 CPR 가이드 자동 활성화 및 실시간 피드백
- 🔗 https://github.com/myDdoDdomi/PushOfLife

---

### 4️⃣ UNISON — AI 기반 UN SDG 연계 학습 플랫폼 (LMS) · 단독 개발
> ㈜로그엔코딩 재직 중, 학원생의 UN SDGs 활동을 지원하기 위해 단독 설계·구현한 AI LMS

**Role** · 단독 개발 (서버사이드 API 설계·전체 구현)
**Stack** · `TypeScript` `Firebase Functions (Node.js)` `Firestore` `OpenAI API (GPT-4o-mini)` `GCP Secret Manager`

- GPT-4o-mini로 SDG 연계 8주 커리큘럼 자동생성·AI 채점 API 구현
- Firestore 소유권 기반 보안 규칙 작성, 소프트삭제(휴지통) 패턴 적용
- OpenAI 키를 GCP Secret Manager로 분리 관리
- 🔗 https://github.com/myDdoDdomi/pjt-unison

---

### 🧪 Side · Network Protocol 시각화 교육 (개인)
> TCP/UDP 게임 서버 구현으로 네트워크 프로토콜 원리를 가르치는 교육 시뮬레이션

`C++` `Python (Socket)` — Login(TCP)/Game(UDP) 서버 분리 설계로 교육생의 프로토콜 이해를 도움

---

## 🏅 Awards & Certifications
* 🏆 **SSAFY 프로젝트 우수팀 수상** (공통/자율 프로젝트, 결선 발표회 1위 — 삼성전자)
* 👨‍🏫 **SSAFY 실습 코치** — 교육생 기술 멘토링 및 디버깅 지원
* 📜 **정보처리기사** (2025)
* 🗣 **JLPT N2** · **OPIc IM2**

---

<div align="center">
  <h3>📫 Contact</h3>
  <a href="mailto:gumtteun@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <a href="https://bong-pf-pjt.web.app/">
    <img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=googlechrome&logoColor=white" />
  </a>
  <br><br>
</div>
