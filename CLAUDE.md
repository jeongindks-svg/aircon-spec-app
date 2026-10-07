# 업데이트 규칙

앱을 수정(기능·화면·데이터)할 때마다 아래 세 곳을 항상 같이 올린다.

1. `index.html`의 `APP_VERSION` (예: '1.8' → '1.9')
2. `index.html`의 `CHANGELOG` 맨 위에 새 항목 추가 (버전, 날짜, 변경 내용을 쉬운 한국어로)
3. `sw.js`의 `VERSION` (`aircon-spec-v1.9`처럼 APP_VERSION과 맞춤, 캐시 갱신용)
