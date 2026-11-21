# barun-insurance
바른보험 리모델링 비교제안 시스템

## 고객용 홍보 사이트 (`site/`)

상담 신청을 받는 광고용 랜딩 페이지입니다. Netlify에 이 저장소를 연결하면 `netlify.toml` 설정에 따라 `site/` 폴더만 공개됩니다.

- 상담 신청은 Netlify Forms(`consult`)로 접수됩니다.
- 고객 후기는 `site/index.html` 하단의 `REVIEWS` 배열에 넣으면 표시됩니다. 비어 있으면 후기 영역이 숨겨집니다.
- 공개 전에 푸터의 `[ ]` 항목(소속, 등록번호, 심의필 등)을 실제 정보로 바꿔야 합니다.
