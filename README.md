# benz-taesoo.github.io

벤츠 공식딜러 김태수(구리전시장) 상담 페이지.

## 올리는 방법 (GitHub Pages)
1. GitHub에 `benz-taesoo` 계정으로 로그인합니다. (계정명에는 밑줄을 쓸 수 없어 하이픈으로 정했습니다.)
2. 새 저장소를 `benz-taesoo.github.io` 이름, Public으로 만듭니다.
3. 저장소 화면에서 Add file → Upload files를 누르고, 이 폴더의 `index.html`, `.nojekyll`, `img` 폴더, `data` 폴더를 통째로 끌어다 놓은 뒤 Commit changes를 누릅니다.
4. 1~2분 뒤 https://benz-taesoo.github.io 에서 열립니다. (Settings → Pages에서 Branch가 main / root인지 확인)

## 매달 바꿀 곳 (index.html)
- 히어로 문구와 가격: `11월 최대 20%` 부분
- 아래 숫자 데이터: 파일 하단 `<script>` 안의 `CORE`(핵심 차종), `CALC`(계산기 할인율), `MODELS`의 `promo`(차종별 11월 조건), `NEWS`(신차 소식)
- 하단 고지의 가격표 · 프로모션 기준일

## 차종 상세 창
- 차종 카드를 누르면 `data/detail.json`의 트림 가격, 옵션, 외장 색상, 실내 시트가 열립니다.
- 색상 · 시트 사진은 차종별로 한 장씩 묶어 `img/s/` 폴더에 있습니다 (공식 카탈로그 발췌).
