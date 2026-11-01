# 🐊 croc-chomp

입 벌린 악어의 이빨을 하나씩 누르다가, 운 나쁘면… **콱!** 물리는 3D 운 게임.

- 이빨 16개 중 하나가 무작위 꽝
- 눈, 몸, 꼬리, 코를 터치하면 악어가 반응해요
- 드래그해서 돌려볼 수 있어요

Three.js로 만든 HTML 파일 하나라서 빌드 없이 GitHub Pages로 바로 배포돼요.

## 로컬에서 실행

```bash
python -m http.server 5173
```

브라우저에서 http://localhost:5173 을 열면 돼요.

## DOPA# 브랜드 프레임

`dopasharp/` 폴더는 모든 DOPASHARP 게임 저장소에 **똑같이** 복사해 쓰는 공통 디자인 시스템(v1.0)입니다. 원본은 `soju-game/dopasharp/`이고, 여기서 고치지 말고 원본을 고친 뒤 모든 저장소에 다시 복사합니다. 게임 화면 색은 각 게임이 유지하고, 시작·결과·공유·다른 게임 이동·하단 브랜드 표시만 통일합니다.

- `tokens.css` — 색상·타이포·여백·모서리·모션 토큰.
- `components.css` — 헤더, 버튼(Primary/Secondary/Tertiary), 게임 카드, 결과 시트, 푸터.
- `dopasharp.js` — 게임 목록(`GAMES`), 결과 시트 `DopaSharp.showResult()`, 다른 게임 시트, 공통 분석 이벤트 `DopaSharp.track()`.

링크 미리보기 이미지는 `og/croc.html`을 고친 뒤 `og/croc.png`로 다시 렌더링합니다 (명령은 파일 맨 위 주석 참고).
