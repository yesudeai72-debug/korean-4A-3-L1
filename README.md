# 서울대 한국어 4A · 듣기 1

서울대 한국어 4A 3과 듣기 1(Track 28)의 빈칸 듣기 연습 웹앱입니다.

## 기능

- 문맥 속 14개 어휘·표현 빈칸 입력
- 정답 확인, 정답 보기, 다시 하기
- Track 28 음원 재생과 5초 앞·뒤 이동
- 0.5배속, 0.6배속, 0.75배속, 정상 속도 재생

## 실행

별도 설치가 필요 없는 정적 웹페이지입니다. `index.html`을 브라우저로 열거나, 폴더에서 아래 명령을 실행한 뒤 `http://localhost:4173`으로 접속합니다.

```bash
python3 -m http.server 4173
```

## 파일

- `index.html`: 웹앱 화면과 동작
- `track28.mp3`: 듣기 1 음원

## GitHub에 올리기

GitHub에서 빈 저장소를 만든 다음, 아래의 `YOUR-REPOSITORY-URL`을 새 저장소 주소로 바꾸어 실행합니다.

```bash
git remote add origin YOUR-REPOSITORY-URL
git push -u origin main
```
