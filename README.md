<h1 align="center">Backend & AI Engineer</h1>

<p align="center">
  사용자 문제를 <b>안정적인 백엔드 API</b>와 <b>AI 워크플로</b>로 연결합니다.<br />
  Java · Spring Boot 기반 서비스 설계부터 Python · FastAPI 기반 AI 서비스 연동까지 구현합니다.
</p>

---

## About me

- 도메인 요구사항을 API, 데이터 모델, 예외 처리, 인증/인가까지 일관된 서비스 구조로 구현합니다.
- LLM·Vision·임베딩을 제품 기능에 연결하고, Spring Boot 백엔드와 독립 AI 서버가 협업하는 흐름을 설계합니다.
- 공공데이터 수집, 외부 API 연동, 파일·이미지 처리, 배포 자동화처럼 서비스 운영에 필요한 문제를 끝까지 해결합니다.

## Tech stack

**Backend**

![Java](https://img.shields.io/badge/Java-17%2B-007396?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring%20Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white)
![JPA](https://img.shields.io/badge/JPA%20%2F%20Hibernate-59666C?style=flat-square&logo=hibernate&logoColor=white)
![QueryDSL](https://img.shields.io/badge/QueryDSL-4479A1?style=flat-square)

**AI & Data**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)

**Infrastructure**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

## Featured projects

| Project | What I built | Tech |
| --- | --- | --- |
| [SEED+](https://github.com/TEAM-SEED-PLUS/SEED-PLUS-BACKEND) | 상권·업종·지역 데이터를 바탕으로 창업 의사결정을 돕는 서비스. 공공데이터 수집 및 정제, 동적 계산기 연동, 분석 API와 운영 배포를 구현했습니다. | Java 21, Spring Boot, JPA, QueryDSL, Flyway, PostgreSQL, AWS |
| [CommuteMate](https://github.com/konkuk-icteam-student/CommuteMate-backend) | 출근부·업무일지 통합 플랫폼. 근무 신청·근태·관리자 시간표/인력 관리 API를 구현하고, 권한·시간대·페이징 이슈를 개선했습니다. | Java, Spring Boot, Spring Security, JPA, PostgreSQL, Docker |
| [ORE Backend](https://github.com/ORE-OwnRepairExtend/Back) · [ORE AI](https://github.com/ORE-OwnRepairExtend/AI) | 제품을 오래 쓰도록 돕는 제품 생애주기 관리 서비스. 제품·수리·알림·매뉴얼·채팅 API와 AI 서버를 함께 구현했습니다. Vision OCR로 제품 정보를 추출하고, 공식 매뉴얼 검색·요약 및 문맥 기반 AI 채팅을 제공합니다. | Spring Boot, FastAPI, OpenAI Vision/LLM, PostgreSQL, AWS S3, EC2 |
| [CISP](https://github.com/KT-AIVLE-BIGPROJECT-AI-1/BE) | CCTV·음성·수사 문서를 분석하는 AI 경찰 수사 지원 시스템. 분석 콜백, 음성 전사·진술 모순, 법리 평가, 보고서·감사 로그 API를 구현했습니다. | Java 21, Spring Boot, WebFlux, FastAPI, GPT-4o, Gemini, PostgreSQL, AWS |

## How I approach a service

```text
Requirements
    ↓
Domain model & API design
    ↓
Authentication · validation · exception handling
    ↓
Data / external API / AI service integration
    ↓
Docker & cloud deployment
```

## Highlights

- **Backend foundation** — JWT 인증·인가, Refresh Token, 역할 기반 접근 제어, 공통 응답과 전역 예외 처리를 여러 서비스에 적용했습니다.
- **Data-driven services** — 공공데이터 수집·정제와 마이그레이션(Flyway), PostgreSQL 기반 조회·분석 기능을 구현했습니다.
- **AI in production flows** — GPT·Gemini·Vision·임베딩을 별도 AI 서버로 구성하고, 백엔드의 비즈니스 흐름과 안전하게 연결했습니다.
- **Operational mindset** — Docker, GitHub Actions, AWS S3·EC2·ECR·ECS·CodeBuild를 활용한 실행·배포 환경을 다뤘습니다.

---

<p align="center">
  <a href="https://github.com/woo319">GitHub</a>
</p>
