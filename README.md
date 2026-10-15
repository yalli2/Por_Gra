# 브라질 포르투갈어 문법 · Por_Gra

*Grammar of Spoken Brazilian Portuguese* 의 서론(발음·철자), Lesson I~XXIX, 부록(동사 변화표 §145–175)을 한국어로 정리한 인터랙티브 학습 사이트입니다. 현대 철자법(신정서법)을 기준으로 표기했습니다.

- **메인 페이지**: `index.html` — 31개 단원 카드, 검색, 필터, 학습 진도, 추천 학습 순서
- **단원 페이지**: `Intro/`, `Lesson1/` ~ `Lesson29/`, `Appendix/` — 핵심 설명(문법 표·예문), 소리 듣기(TTS), 연습문제 5종, 채점(점수·정답·해설)
- **연습문제 5종**: ① 뜻 고르기 ② 포르투갈어 고르기 ③ 빈칸 채우기 ④ 듣고 고르기 ⑤ 직접 쓰기(악센트 누락은 0.5점, 악센트 입력 도우미 제공) — 총 약 1,300문항
- 학습 기록과 이름은 브라우저(localStorage)에 저장됩니다. 라이트/다크 모드 지원.

## 사용
GitHub Pages: `https://yalli2.github.io/Por_Gra/`
각 단원은 `https://yalli2.github.io/Por_Gra/LessonN/` 형식입니다.

## 구조
```
index.html            메인
assets/style.css      공통 스타일
assets/lesson.js      단원 페이지 로직(렌더링·채점·TTS)
LessonN/index.html    각 단원 데이터(설명·연습문제)
Intro/, Appendix/     서론, 부록
```
