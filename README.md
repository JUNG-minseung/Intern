# Intern – JWT 인증 API 서버

Node.js 기반의 RESTful API 서버로, 사용자 회원가입, 로그인, JWT 인증 기능을 제공합니다.  
AWS EC2에 배포되어 있으며 Swagger 문서를 통해 전체 API를 확인할 수 있습니다.

🔗 배포 주소: [http://3.107.86.115:3000/api-docs] (http://3.107.86.115:3000/api-docs)

---

## 🚀 주요 기능

- 회원가입 API (/api/signup)
- 로그인 API (/api/login)
- JWT 기반 인증 및 프로필 조회 (/api/profile)
- Swagger 기반 API 명세 제공
- AWS EC2 서버에 직접 배포
- Jest 기반 테스트 구성 가능

---

## 🛠 기술 스택

- Node.js 18.x
- Express.js
- JWT (jsonwebtoken)
- dotenv
- Swagger (swagger-ui-express, swagger-jsdoc)
- PM2 (운영 환경에서 백그라운드 실행)
- AWS EC2 (Ubuntu 22.04 LTS)

---

## 📦 프로젝트 구조
Intern/
├── controllers/
├── middlewares/
├── routes/
├── tests/
├── utils/
├── models/
├── app.js
├── server.js
├── .env (로컬에서 직접 작성)
├── package.json
└── README.md
