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
* **비즈니스 데이터 시각화**: 대규모 고객 데이터를 체계적으로 관리하고 대시보드 형태로 시각화하여 의사결정 효율성 증대
* **엔드투엔드(End-to-End) 구현**: 백엔드 API 설계부터 프론트엔드 UI, CI/CD 배포 파이프라인까지 전체 스택의 기술적 완성도 확보

#### **💻 개발 내용**
* **Backend & Security**
    * **FastAPI & SQLAlchemy**를 활용한 비동기 기반 고성능 RESTful API 설계 및 구축
    * **PostgreSQL**을 이용한 비즈니스 데이터 모델링 및 효율적인 관계 매핑
* **Frontend & State Management**
    * **React & TypeScript**를 사용하여 타입 안정성이 확보된 대시보드 UI 개발
    * **Zustand** 기반의 전역 상태 관리를 통해 대시보드 내 실시간 데이터 동기화 최적화
* **Infra & DevOps**
    * **GitHub Actions**를 활용한 자동화된 CI/CD 파이프라인 구축
    * **Vercel**(Front-end)과 **Render**(Back-end)를 활용한 전략적 배포 및 운영
      
#### **📈 핵심 구현 내용 **
* **매핑 엔진**: 계정 코드와 코스트 센터(부서) 정보를 기준으로 원장 데이터를 KPI 카테고리에 자동 매
* **드릴다운(Drill-down) 기능**: 요약 지표 클릭 시 상세 원장 리스트 및 수기 보정액을 합산하여 조회하는 모달 UI 구현
* **리포트 내보내기**: html2canvas 기반 PDF 다운로드 기능 구현 및 CSS 컬러 스페이스(oklch) 정규화를 통한 렌더링 결함 해결
* **마감(Lock) 시스템**: 월별 데이터 마감 기능을 통해 매핑 정보가 변경되어도 과거 데이터의 스냅샷 유지가 가능하도록 설계

**📊 성과**
- 50MB xlsx → DB 자동 적재 처리 시간 5초 이내 달성. 월간 수작업 집계 업무 완전 자동화 (기존 수시간 → 자동화)
- 기능 명세서 기반 필수 핵심 기능(A등급) 구현 완 및 프로덕션 빌드 성공
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
> **Gemini & 앨런 AI 기반 AI 면접 플랫폼**  
> 맞춤형 면접 질문 생성, AI 피드백, 커뮤니티 및 랭킹 기능 제공

**📌 담당 역할**
- **커뮤니티 기능 풀스택 구현**
  - 게시글 / 댓글 / 좋아요 / 스크랩 CRUD API 구현
  - User 연관관계 매핑 → 작성자 정보 함께 조회
  - 카테고리·난이도·키워드 기반 검색 및 필터링
  - Spring Data JPA + Specification 기반 동적 쿼리
- **데이터베이스 관리**
  - ERD 설계 및 Flyway 마이그레이션 전담
  - User 중심으로 Community / Interview / Ranking 구조 설계
  - 팀 협업 시 DB 버전 충돌 방지를 위한 규칙 정립
- **발표**
  - 최종 발표 준비 및 커뮤니티 파트 시연

**📊 성과**
- 상호작용 중심 커뮤니티 모듈 구현
- Flyway 도입으로 DB 이력 관리 체계화
- 기술 내용을 구조적으로 설명하는 발표 경험 확보

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

