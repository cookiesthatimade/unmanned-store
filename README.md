# 👚 vue-unmanned-store-web 👚



> 무인의류매장 플랫폼 운영을 위한 웹
<img src="https://github.com/user-attachments/assets/5c7c437a-0c05-4ef5-9d65-c69fea5890c0">

---

## 📖 프로젝트 소개

**vue-unmanned-store-web**은 AI 기반 무인의류매장 내 점원로봇에 탑재된 웹 서비스로, 고객을 위한 매장 안내 및 판매, 개인화 및 사용자 평가 등의 기능을 제공합니다.

### 🔹 주요 기능

1. **상품 판매**
   - 상품(Woman,Men), 관심상품, 장바구니
2. **결제**
   - 포트원(PortOne) 연동을 통해 안전한 온라인 결제 가능
3. **설문조사**
   - 설문조사를 통해 사용자들의 만족도 데이터 수집

---
## 🎥 데모

<p align="left">
    <img src="https://github.com/user-attachments/assets/5c7c437a-0c05-4ef5-9d65-c69fea5890c0" width="500">
    <img src="https://github.com/user-attachments/assets/470070f9-762d-4a62-a0c4-5c82d246b0bc" width="500">
    <img src="https://github.com/user-attachments/assets/f9c357a8-960e-4bf2-aa1b-ba44bb7cfbec" width="500">
    <img src="https://github.com/user-attachments/assets/58ff0652-a225-49df-9cad-78fee5e8cbe1" width="500">
    <img src="https://github.com/user-attachments/assets/57c41492-5458-4822-b244-4ae4a338414d" width="500">
    <img src="https://github.com/user-attachments/assets/70c31a17-d536-464a-b60f-936c4601f8ac" width="500">
    <img src="https://github.com/user-attachments/assets/679ee67f-efe2-46d7-ac61-dbc2af9bb3b7" width="500">
    <img src="https://github.com/user-attachments/assets/c0a06c40-2168-43fc-8ee7-cc9273e168c1" width="500">
</p>

---

## ⭐ 핵심 기술

### 🧩 Node.js & Express.js

- **RESTful API**를 사용하여 사용자 및 설문조사 데이터 관리

### 🗄 데이터베이스 & 실시간 데이터 처리

- **커넥션풀**을 활용하여 효율적인 데이터베이스 연결 관리
- 사용자 정보 및 설문조사 데이터 저장 및 조회

### 💳 온라인 결제 시스템 구축

- **포트원(PortOne)** 연동 통한 온라인 결제 시스템 구축

### 🌍 웹 접근성 및 반응형 디자인 적용

- 다양한 디바이스에서 최적화된 UI 제공

---

## 💻 프로젝트 실행 방법

### 프론트 접속
```
cd frontend
```
### 개발 서버 실행
```
npm run serve
```
### 빌드
```
npm run build
```
### 백엔드 접속
```
cd backend
```
### 서버 실행
```
npm start
```
### ➡️ Go to localhost:8080

---

## 🔧 기술 스택

| **분류**            | **기술**                        |
| ----------------- | ----------------------------- |
| **언어**            | HTML, CSS, JavaScript |
| **라이브러리 & 프레임워크** | Vue.js, Node.js, Express.js  |
| **데이터베이스**        | MySQL                         |
| **결제 시스템** | 포트원(PortOne) |
| **배포 환경**         | AWS EC2, Docker               |
| **실행 환경**         | Node.js                      |
---

## 📁 프로젝트 구조

```markdown
📦 src
├── 📂 backend                # 백엔드 (Node.js & Express.js)  
│   ├── 📂 bin                # 서버 실행 관련 스크립트  
│   ├── 📂 node_modules       # NPM 패키지 모듈  
│   ├── 📂 public             # 정적 파일 (이미지, CSS 등)  
│   ├── 📂 routes             # API 라우트 (Express 라우터)  
│   ├── 📂 views              # 템플릿 파일 (EJS 등)  
│   ├── 📄 .env               # 환경 변수 설정 파일  
│   ├── 📄 app.js             # Express 서버 엔트리 파일  
│   ├── 📄 package.json       # 백엔드 종속성 및 설정  
│   ├── 📄 package-lock.json  # NPM 패키지 버전 관리  
│   ├── 📄 README.md          # 백엔드 설명 문서  
│   └── 📄 .DS_Store          
│  
├── 📂 frontend               # 프론트엔드 (Vue.js)  
│   ├── 📂 public             # 정적 파일 (index.html 포함)  
│   ├── 📂 src                # Vue.js 소스 코드  
│   ├── 📄 vue.config.js       # Vue 프로젝트 설정  
│   ├── 📄 babel.config.js     # Babel 설정  
│   ├── 📄 jsconfig.json       # JavaScript 프로젝트 설정  
│   ├── 📄 package.json        # 프론트엔드 종속성 및 설정  
│   ├── 📄 package-lock.json   # NPM 패키지 버전 관리  
│   ├── 📄 README.md           # 프론트엔드 설명 문서  
│   ├── 📄 .gitignore          
│   └── 📄 .DS_Store  
```

---

## 👨‍💻 역할 및 기여

| 역할                 | 담당 업무                                                         |
| ------------------ | ------------------------------------------------------------- |
| **Backend (Web)**  | Node.js, Express.js, MySQL       |
| **DevOps**         | AWS EC2, Docker                         |
| **Etc**             | 데이터베이스 운영, 보안 설정 |

---

## 👨‍👩‍👧‍👦 Developer
*  **김성하** ([cookiesthatimade](https://github.com/cookiesthatimade))
*  **김성욱** ([seonguk0893](https://github.com/seonguk0893))
