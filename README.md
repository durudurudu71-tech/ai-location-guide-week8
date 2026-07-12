# 나만의 위치 안내 서비스

Node.js와 Express로 만든 아주 간단한 웹앱입니다.
카카오맵 JavaScript SDK를 사용해 지도 화면을 보여 줍니다.

## 실행 방법

1. 바탕화면의 `AI_위치안내_8주차` 폴더를 엽니다.
2. 폴더 안에서 터미널을 엽니다.
3. 아래 명령어를 한 번 실행합니다.

```bash
npm install
```

4. 서버를 실행합니다.

```bash
npm start
```

5. 브라우저에서 아래 주소로 접속합니다.

```text
http://localhost:3000
```

## 파일 설명

- `server.js`: Express 서버 파일입니다. Render에서는 `PORT` 환경 변수를 사용하고, 로컬에서는 3000번 포트로 실행됩니다.
- `public/index.html`: 화면에 보이는 글자와 카카오맵 스크립트를 작성한 파일입니다.
- `public/style.css`: 화면과 지도 영역 디자인 파일입니다.
- `package.json`: 실행 명령어와 필요한 Express 정보를 담은 파일입니다.
