# 📍 나만의 위치 안내 서비스

원하는 장소의 위치를 쉽고 빠르게 안내해 주는 웹 애플리케이션입니다.

## 🛠 기술 스택

| 구분 | 기술 |
|------|------|
| 서버 | Node.js + Express |
| 프론트엔드 | HTML, CSS |
| 지도 | 카카오맵 (배포 후 연결 예정) |

## 📁 프로젝트 구조

```
AI_위치안내_8주차/
├── server.js          # Express 서버 (포트 3000)
├── public/
│   └── index.html     # 메인 웹페이지
├── package.json       # 프로젝트 설정
└── .gitignore         # Git 제외 파일 목록
```

## 🚀 실행 방법

### 1. 프로젝트 클론

```bash
git clone git@github.com:durudurudu71-tech/ai-location-guide-week8.git
cd ai-location-guide-week8
```

### 2. 패키지 설치

```bash
npm install
```

### 3. 서버 실행

```bash
node server.js
```

### 4. 브라우저 접속

```
http://localhost:3000
```

## 📌 참고

- 현재는 기본 UI만 구현된 상태입니다.
- 카카오맵 API는 배포 후 연결할 예정입니다.
