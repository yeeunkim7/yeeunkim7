# 👋 안녕하세요, 백엔드 개발자 김예은입니다

Java/Spring Boot 백엔드 개발자입니다.
EST Lab 인턴십에서 ERP 대시보드를 1인 풀스택으로 
설계부터 실서비스 배포까지 완료했습니다.
회계 실무 4년의 데이터 정합성 감각을 백엔드 설계에 적용합니다.

---

## 💼 Experience

### **East Lab**
> **Backend Developer Intern** | 2026.02 - 2026.03
- EST-CRM-Dashboard 구축: 엑셀 기반의 영업/매출 관리 프로세스를 대시보드 시스템으로 완전 자동화
- Full-stack Ownership: DB 설계부터 백엔드 API, 프론트엔드 UI, 배포까지 전 과정 1인 전담 개발


#### **프로젝트 목표**
* **비즈니스 데이터 시각화**: 부서별 매출·비용 데이터를 KPI 카드·피벗 그리드·Drill-down 형태로 시각화
* **업무 자동화**: 담당자가 매월 수작업으로 처리하던 엑셀 집계 업무를 ETL 파이프라인으로 대체
  
#### **💻 개발 내용**
* **Backend & Security**
    * **FastAPI & SQLAlchemy**를 활용한 비동기 기반 RESTful API 설계 및 구축
    * MS OAuth2 + JWT RBAC 3단계 권한 시스템 전체 설계
    * **PostgreSQL** 기반 비즈니스 데이터 모델링
* **Frontend & State Management**
    * **React & TypeScript** 기반 대시보드 UI 개발
    * **Zustand** 전역 상태 관리로 대시보드 데이터 동기화
* **Infra & DevOps**
    * **Vercel**(Frontend)과 **Render**(Backend) 분리 배포.
      Git push 시 자동 배포로 별도 배포 작업 없이 운영
    * 환경변수(dev/prod) 분리로 로컬과 운영 설정을 코드 변경 없이 전환
      
#### **📈 핵심 구현 내용 **
* **ETL 파이프라인**: 50MB xlsx → 컬럼 검증 → DB 적재 → 실패 시 전체 롤백. Pandas 유효성 검사기로
  잘못된 데이터 DB 적재 사전 차단
* **RAG 챗봇**: GPT-4o-mini + pgvector 기반 KPI 챗봇 구현.
  평균 응답 5.3초 (임베딩 1.0s · 벡터검색 0.6s · LLM 3.6s)
* **Drill-down 기능**: 요약 지표 클릭 시 상세 원장 리스트 및 수기 보정액을 합산 조회하는 모달 UI 구현
* **마감(Lock) 시스템**: 월별 데이터 마감으로 매핑 정보가 변경되어도 과거 데이터 스냅샷 유지

**📊 성과**
- 50MB xlsx → DB 자동 적재 처리 시간 5초 이내 달성. 월간 수작업 집계 업무 완전 자동화 (기존 수시간 → 자동화)
- 기능 명세서 기반 필수 핵심 기능(A등급) 구현 완료 및 프로덕션 배포 성공
---

## 🛠️ 기술 스택

### 👩‍💻 Language & Framework
![Java](https://img.shields.io/badge/Java-007396?style=flat&logo=java&logoColor=white)
![Spring Boot](https://img.shields.io/badge/SpringBoot-6DB33F?style=flat&logo=spring-boot&logoColor=white)
![JPA](https://img.shields.io/badge/JPA-%23007ACC?style=flat)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-005850?style=flat&logo=fastapi&logoColor=white)

### 🛡️ Security & Auth
![Spring Security](https://img.shields.io/badge/SpringSecurity-6DB33F?style=flat&logo=spring&logoColor=white)
![OAuth2](https://img.shields.io/badge/OAuth2-EB5424?style=flat&logo=openid&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat&logo=jsonwebtokens)

### 🗄️ Database
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat&logo=postgresql&logoColor=white)

### ☁️ DevOps & Infra
![AWS](https://img.shields.io/badge/AWS-232F2E?style=flat&logo=amazon-aws)
![EC2](https://img.shields.io/badge/EC2-F58536?style=flat&logo=amazon-ec2&logoColor=white)
![S3](https://img.shields.io/badge/S3-569A31?style=flat&logo=amazon-s3&logoColor=white)
![Render](https://img.shields.io/badge/Render-46E3B7?style=flat&logo=render&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=github-actions&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat&logo=vercel&logoColor=white)

### 🛠️ Frontend & ETC
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![HTML](https://img.shields.io/badge/HTML-E34F26?style=flat&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-1572B6?style=flat&logo=css3&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

---

## 💼 프로젝트

### 🤖 AI 기반 개발자 모의 면접 시뮬레이터 - DevView
> **Gemini & 앨런 AI 기반 면접 플랫폼**
> 직무별 면접 질문 생성, AI 피드백, 커뮤니티 기능 제공

**📌 담당 역할**
- **ERD 설계 및 Flyway 마이그레이션 전담**
  - 전체 서비스 ERD 주도 설계
  - Users · Interviews · InterviewResults · Community 등
    11개 테이블 관계 정의 및 정규화
  - Flyway 도입으로 환경 간 스키마 불일치 에러 0건 달성
- **커뮤니티 도메인 백엔드 구현**
  - 게시글 / 댓글 / 좋아요 / 스크랩 REST API 24개 구현
  - 직무·키워드 검색, 페이징, 중복 방지 로직 포함
  - Spring Data JPA + Specification 기반 동적 쿼리

**📊 성과**
- Flyway 도입 후 환경 간 스키마 충돌 0건
- 커뮤니티 API 24개 구현 및 팀 전체 배포 완료
- 우수상 수상 (전체 팀 중)

**🔗 링크**
- [서비스 배포](https://devview.kro.kr/)
- [시연 영상](https://youtu.be/cSnN2AwqB2s)
- [GitHub Repository](https://github.com/yeeunkim7/DevView)

---

### 🥕 당근마켓 클론코딩  
> Spring 기반 지역 커뮤니티 & 중고거래 플랫폼

**📌 담당 역할**
- Spring Security 기반 로그인/회원가입 인증 로직 구현
- Google OAuth2 소셜 로그인 연동
- AWS EC2 배포 및 S3 이미지 업로드 구성
- PostgreSQL 연동 및 세션 기반 인증 흐름 구현

**🔗 GitHub**
- https://github.com/yeeunkim7/Danggeun

---

### 🧩 React SNS Practice (개인 학습 프로젝트)
> React + TypeScript 기반 SNS 핵심 기능 구현 연습 프로젝트

기존 SNS 서비스 구조를 참고하여,  
**프론트엔드 환경에서 인증·상태 관리·데이터 흐름을 이해하기 위한  
클론 기반 학습 프로젝트**입니다.

**📌 구현 및 학습 내용**
- Supabase Auth 기반 이메일 / 소셜 로그인
- RLS(Row Level Security)를 활용한 사용자별 데이터 접근 제어
- TanStack Query 기반 피드 무한 스크롤
- 좋아요 기능 캐시 정규화 및 상태 관리
- 작성자 본인 포스트에 한해 수정/삭제 가능하도록 권한 제어
- Zustand 기반 전역 상태 및 테마 관리

**🔗 GitHub**
- https://github.com/yeeunkim7/react-sns-practice

## 🚀 현재 진행 중

### Ready-Hire - AI 모의면접 서비스 (개발 중)
> Spring Boot 3.x + GPT-4o-mini 기반 실서비스 출시 목표

- 무료/유료 구독 모델 (포트원 결제 연동)
- JWT + Google OAuth2 인증
- 하루 3회 무료 제한 / PRO 플랜 무제한
- Google Play / App Store 출시 예정

---

## 📫 Contact

- ✉️ Email: tyeole7172@naver.com

