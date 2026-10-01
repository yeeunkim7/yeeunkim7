# 👋 안녕하세요, 백엔드 개발자 김예은입니다

Java / Spring 기반 백엔드 개발자입니다.

회계·사업관리 실무를 경험하며 데이터의 정확성과 업무 프로세스의 중요성을 배웠고,
현재는 이를 바탕으로 데이터 정합성과 안정적인 처리 흐름을 만드는 백엔드 개발에 집중하고 있습니다.

ERP 대시보드 개발 인턴십에서 재무 데이터의 검증 → 적재 → 조회 → 마감 흐름을 직접 구현했으며,
Java/Spring 프로젝트를 통해 REST API, 인증/인가, 데이터베이스 설계와 트랜잭션 처리를 학습하고 있습니다.

단순히 기능이 동작하는 것보다
데이터가 어디에서 들어와 어떻게 처리되고 저장되는지 이해할 수 있는 시스템을 만드는 것을 중요하게 생각합니다.

---

## 💼 Experience

### **East Lab**
> **Backend Developer Intern** | 2026.02 - 2026.03
- EST-CRM-Dashboard 구축: 엑셀 기반 영업·재무 데이터 관리 프로세스를 ERP 대시보드로 자동화
- 개발 담당 1인으로 DB 설계부터 백엔드 API, 프론트엔드 UI, 배포까지 전 과정 개발

#### **프로젝트 목표**
* **비즈니스 데이터 시각화**: 부서별 매출·비용 데이터를 KPI 카드·피벗 그리드·Drill-down 형태로 시각화
* **업무 자동화**: 담당자가 매월 수작업으로 처리하던 엑셀 집계 업무를 ETL 파이프라인으로 대체
  
#### **💻 개발 내용**
* **Backend & Security**
    * **FastAPI & SQLAlchemy**를 활용한 RESTful API 설계 및 구축
    * 이메일 인증 및 MS OAuth2 + JWT 기반 RBAC 권한 관리
    * Viewer 부서별 데이터 격리 및 Admin 전사 데이터 조회 권한 분리
    * **PostgreSQL** 기반 ERP 데이터 모델링
    * 부서별 매출·비용 KPI Dashboard 구현
    * 월별 데이터 변경을 제한하는 마감(Lock) 기능 구현
* **Frontend & State Management**
    * **React & TypeScript** 기반 대시보드 UI 개발
    * **Zustand** 전역 상태 관리로 대시보드 데이터 동기화
* **Infra & DevOps**
    * **Vercel**(Frontend) / **Render**(Backend) 분리 배포.
    * Git push 시 자동 배포로 별도 배포 작업 없이 운영
    * dev / prod 환경변수 분리를 통한 환경별 설정 관리
      
#### 📈 핵심 구현 내용 
* **ETL 파이프라인**
  * 50MB xlsx → 필수 컬럼 검증 → 데이터 매핑 → DB 적재 → 오류 발생 시 전체 Rollback
  * Pandas 기반 유효성 검사기로 잘못된 데이터의 DB 적재를 사전 차단
  * 계정·부서 미매핑 데이터를 자동 탐지하고 등록할 수 있도록 처리
    
* **RAG 챗봇**
  * LangChain + GPT + pgvector 기반 KPI 질의 기능 구현
  * 임베딩 → Vector Search → LLM 응답 흐름 적용
  
* **Drill-down 기능**
  * 요약 KPI에서 상세 원장 데이터를 확인할 수 있는 조회 기능 구현
  
* **마감(Lock) 시스템**
  * 월별 데이터 마감 후 매핑 정보가 변경되더라도 과거 데이터 기준을 유지하도록 설계

**📊 성과**
- 1만 행 기준 Excel 업로드 **30초 이내**, KPI 조회 **5초 이내** 성능 검증
- 수작업 Excel 데이터 검증·집계 프로세스를 시스템 기반으로 자동화
- 핵심 기능 MVP 구현 및 서비스 배포 완료
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

### 🔄 거래 대사 자동화 시스템 (개인 프로젝트)
> **Java / Spring Boot 기반 거래·정산 데이터 대사 시스템**

회계 실무에서 경험한
**은행 입출금 내역과 서비스 이용·정산 내역을 수작업으로 대조하는 업무**를
백엔드 시스템으로 자동화하기 위해 개발하고 있는 개인 프로젝트입니다.

기존 Excel 중심 업무에서 발생할 수 있는
중복 적재, 누락, 데이터 불일치 문제를 줄이고
원본 데이터부터 집계 결과까지 추적할 수 있는 구조를 목표로 하고 있습니다.

**📌 구현 내용**

- **거래처 관리**
  - 거래처 등록·조회·수정 기능 구현
  - 다수 거래처 조회를 위한 Batch 처리 적용

- **CSV 데이터 업로드**
  - 업무 데이터 및 은행 거래내역 CSV 업로드 기능 구현
  - Commons CSV 기반 Parsing
  - BOM 및 CSV 형식 검증
  - 파일명과 SHA-256 Hash 값을 저장해 업로드 파일 추적
  - 원본 행 식별값을 활용한 중복 데이터 적재 방지

- **데이터 검증 및 적재**
  - CSV Parsing → Validation → 중복 검사 → Entity 변환 → DB 저장 흐름 구성
  - `@Transactional`을 적용하여 적재 중 오류 발생 시 전체 Rollback
  - 업로드 파일과 실제 거래 데이터를 연결해 원본 데이터 추적 가능하도록 설계

- **대사 데이터 조회**
  - 업무 데이터와 은행 거래 데이터를 기준으로 일별·월별 집계 조회 기능 구현
  - 거래 차이를 확인할 수 있도록 데이터 조회 구조 설계

- **Database Migration**
  - **Flyway**를 이용해 DB Schema 변경 이력 관리
  - 개발 DB와 테스트 DB를 분리해 테스트 수행 시 실제 데이터가 변경되지 않도록 구성

- **Test**
  - 거래처·업로드·조회 기능을 대상으로 통합 테스트 작성
  - 별도 Test Database를 사용해 데이터 독립성 확보

**📌 데이터 처리 흐름**

```text
CSV 파일 업로드
      ↓
파일 / 데이터 형식 검증
      ↓
CSV Parsing
      ↓
중복 데이터 검사
      ↓
Entity 변환
      ↓
Transaction 기반 DB 적재
      ↓
일별 / 월별 집계 조회
```

---

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

### 🥕 위치 기반 중고거래 플랫
> Java / Spring Boot 기반 위치 검색·중고거래 서비스

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


## 📫 Contact

- ✉️ Email: tyeole7172@naver.com

