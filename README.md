# 안녕하세요, 소채연입니다.
새로운 내용을 배우면 직접 정리하고 적용해보며  
이해한 내용을 제 것으로 만들기 위해 노력합니다.
작은 문제도 그냥 넘기지 않고  
원인을 찾아가며 해결하는 과정을 중요하게 생각합니다.

---

## 🛠 Tech Stack

### Backend
![Java](https://img.shields.io/badge/Java-17-007396?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.x-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![MyBatis](https://img.shields.io/badge/MyBatis-000000?style=flat-square)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express_v5-000000?style=flat-square&logo=express&logoColor=white)
![Oracle DB](https://img.shields.io/badge/Oracle_DB-F80000?style=flat-square&logo=oracle&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)

### Frontend
![JSP](https://img.shields.io/badge/JSP-FF6F00?style=flat-square)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![jQuery](https://img.shields.io/badge/jQuery-0769AD?style=flat-square&logo=jquery&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![MUI](https://img.shields.io/badge/MUI_v6-007FFF?style=flat-square&logo=mui&logoColor=white)

### AI / Data
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SentenceTransformers](https://img.shields.io/badge/SentenceTransformers-222222?style=flat-square)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat-square)
![Google Gemini](https://img.shields.io/badge/Google_Gemini-4285F4?style=flat-square&logo=google&logoColor=white)

### Tools
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white)
![MySQL Workbench](https://img.shields.io/badge/MySQL%20Workbench-4479A1?style=flat-square&logo=mysql&logoColor=white)

---

## 📌 Projects

### 🏕 모닥모닥
캠핑용품 대여와 구매를 함께 제공하는 웹 기반 커머스 프로젝트입니다.

**주요 기능**  
회원가입, 마이페이지, 상품 조회, 장바구니, 주문/결제, 배송조회, 대여, 커뮤니티, 고객센터, 관리자 기능

**담당 역할**
- 로그인/회원가입, 계정 찾기 기능 구현
- 마이페이지 기능 구현
  - 주문 내역, 리뷰 내역, 위시리스트, 최근 본 상품
  - 쿠폰 내역, 포인트 내역
- 멤버십 페이지 구현
- 배송조회 기능 구현
- 통합 검색 기능 구현
- 프로젝트 전체 페이지 CSS 개선 및 UI 스타일 통일 및 부가 기능 추가

---

### 🧠 AdBye
AI 기반 광고성 리뷰 유사도 판별 서비스입니다.  
사용자 리뷰와 DB에 저장된 광고성 리뷰를 비교하여  
유사도 백분율과 가장 유사한 광고성 리뷰를 제공합니다.  
가장 유사한 광고성 리뷰는 두 줄로 요약하여  
시각화 차트 아래에 함께 표시되도록 구현했습니다.

**주요 기능**
- 리뷰 문장 임베딩
- 광고성 리뷰 유사도 분석
- 가장 유사한 광고성 리뷰 표시
- 유사 광고성 리뷰 2줄 요약 제공
- 광고성 여부 판단
- 유사도 결과 시각화

**사용 기술**  
Python · SentenceTransformer · all-MiniLM-L6-v2 · SQLite · Matplotlib · React

---
### ⌨️ CtrlE
코드 공유, 소통, 협업을 위한 **개발자 전용 SNS 플랫폼**입니다.  
혼자 마주치는 에러도, 막히는 코드도 커뮤니티 안에서 함께 해결해 나간다는 의미를 담았습니다.

**주요 기능**  
게시물 작성(마크다운/리치텍스트 에디터), 코드 블록 하이라이팅, 릴스, 실시간 1:1·그룹 채팅,  
좋아요·댓글·북마크, 팔로우 시스템, 알림, 탐색/검색, 마이페이지, 다크모드, 관리자 대시보드

**담당 역할** — 기획 · 설계 · 프론트엔드 · 백엔드 전체(개인 프로젝트)
- 이메일 회원가입/로그인 및 Google·GitHub OAuth 2.0 소셜 로그인 구현
- 마크다운 에디터(Tiptap) + Monaco Editor 기반 코드 하이라이팅 게시물 작성
- 1:1·그룹 채팅 (이모지 리액션, 읽음 표시, 타이핑 인디케이터, 말풍선 커스텀)
- 릴스(동영상 피드), 알림, 탐색/검색, 관리자 기능 구현
- Google Gemini AI 연동

**사용 기술**  
React · MUI · Tiptap · Monaco Editor · Node.js · Express v5 · Oracle DB · JWT · Passport.js · Google/GitHub OAuth · Multer · Nodemailer · Google Gemini

---

## ✨ Interest
- 사용자 흐름을 고려한 기능 설계
- 상태값에 따른 동적 UI 처리
- 예외 상황을 고려한 안정적인 기능 구현
- 사용자가 이해하기 쉬운 화면 구성
- 유지보수하기 쉬운 코드 구조
