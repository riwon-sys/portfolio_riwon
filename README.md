# portfolio_riwon

안녕하세요 👋  
**침착하지만, 끊임없이 성장하며, 본질에 집중하는 개발자 김리원**입니다.  
Spring Boot · React · Flutter 기반의 웹/앱 프로젝트 경험을 통해  
**기획 → DB 설계 → 백엔드 → 프론트엔드 → 배포** 전 과정을 주도적으로 수행했습니다.  

![Backend Developer](https://img.shields.io/badge/Role-Backend%20Developer-blue?style=for-the-badge&logo=springboot)
![QAQC](https://img.shields.io/badge/Role-QA%2FQC%20Engineer-green?style=for-the-badge&logo=react)  
![Growth](https://img.shields.io/badge/Identity-Always%20Calm%20%26%20Growing-orange?style=for-the-badge&logo=flutter)  

---

## 🔑 핵심 기술 스택
- **Backend**: Spring Boot, JPA, MySQL, Redis, JWT  
- **Frontend**: React(Vite, MUI/Joy UI, Recharts), Flutter(Dart)  
- **Tools**: GitHub, Figma, Talend API Tester, Postman  
- **Etc.**: REST API 설계, ERD/DB 모델링, SQL 최적화  

---

## 📌 주요 프로젝트

### 1. DevConnect Admin Web
> 관리자 전용 React 웹 (Spring Boot + React + JWT + Redis)  
- 기업·개발자·프로젝트·평가 관리 대시보드 구현  
- Joy UI + Recharts 기반 통계 시각화  
- JWT 인증 + Role Route 보호 라우팅 적용  

**트러블슈팅 사례**  
- FormData 업로드 오류 → @ModelAttribute + multipart 적용 → 이미지 정상 처리  
- 권한 라우팅 충돌 → PrivateRoute + RoleRoute 개선 → 접근 제어 강화  

**KPT 회고**  
- ✅ Keep: 독립적인 Admin Web 구축, Redis 연동 경험  
- ⚠️ Problem: 초기 FormData 처리 및 라우팅 충돌  
- 💡 Try: 테스트 케이스 확충, Redis 설정/모니터링 강화  

---

### 2. ERP SYS (AssetKeeper)
> 소규모 스타트업용 ERP 시스템  
- 인사·자산·출결·회계 관리 모듈 설계 및 구현  
- Spring Boot + MySQL + JSP (초기 버전) → React/Flutter 확장  

**트러블슈팅 사례**  
- DB 연결 불안정 → Connection Pool 도입 → CRUD 안정화  
- 입력값 검증 누락 → Validation 강화 → 사용자 경험 개선  

**KPT 회고**  
- ✅ Keep: 단독 개발 경험, MVC 패턴 이해 심화  
- ⚠️ Problem: 예외 처리·검증 미흡, DB 안정성 부족  
- 💡 Try: Spring Boot 전환, 견고한 Validation 구조 설계  

---

### 3. WorkPlatform
> Spring Boot + React 기반 팀 협업 프로젝트  
- JWT 인증 기반 사원 관리 시스템  
- RBAC(Role-Based Access Control) 기반 권한별 메뉴 제어  
- Redux Persist 적용으로 로그인 상태 유지  

**트러블슈팅 사례**  
- JWT 만료 처리 누락 → ExpiredJwtException 캐치 → UX·보안 개선  
- Redux 초기화 문제 → Redux Persist 도입 → 로그인 유지  
- 권한 제어 미흡 → Role 체크 강화 → 보안 강화  

**KPT 회고**  
- ✅ Keep: JWT 인증/인가 구현, Redux Persist 적용 성공  
- ⚠️ Problem: 협업 규칙 미흡, Redux 디버깅 어려움  
- 💡 Try: 브랜치 전략·컨벤션 강화, 사전 학습 후 적용  

---

## 📂 포트폴리오 특징
- **End-to-End 경험**: DB 설계부터 UI/UX, 배포까지 직접 수행  
- **실무형 구조**: JWT 인증, RBAC 권한 제어, Redis 세션 관리, FormData 업로드 적용  
- **협업/확장성 고려**: API 문서화, 주석 규칙, Git 브랜치 전략 사용  

---

## 📬 연락처
- Email: **lelabo7317@gmail.com**  
- GitHub: [github.com/riwon-sys](https://github.com/riwon-sys)  

---

✨ 끊임없이 배우고 성장하며, 보이지 않는 곳에서도 묵묵히 최선을 다하는 개발자입니다.
