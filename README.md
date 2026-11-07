# 관심종목 (모바일)

주식 자동분석 결과(가장 최근 `YYYY-MM-DD.xlsx`)의 '매수종목'·'2개월이내' 시트를 휴대폰에서 보는 페이지입니다.

- 주소: https://shield777.github.io/stock-pick/
- 데이터(`data.enc.json`)는 암호화되어 있어 암호 없이는 내용을 볼 수 없습니다.
- 갱신: 매일 06:30 주식 자동분석이 끝난 직후 자동(`C:\Shield77\jupyter\auto\web_export.py`).
- 아이폰: Safari로 주소 접속 → 공유 → "홈 화면에 추가". 안드로이드: Chrome 메뉴 → "홈 화면에 추가".

## 디자인 고치기
- 화면은 `index.html` 한 파일입니다. 색·간격은 맨 위 `:root` 변수에 모여 있습니다.
- GitHub 웹에서 `index.html`을 직접 고쳐 저장해도 되고, PC의 `C:\Users\Shiel\stock-pick`에서 고친 뒤 올려도 됩니다.
- PC에서 고쳤다면 **꼭 올리기(push)까지** 하세요. 매일 자동 갱신은 GitHub 쪽 내용을 먼저 받아온 뒤 데이터만 바꾸므로, 올리지 않은 PC 수정은 덮어써집니다.
