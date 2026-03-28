# 포트폴리오 이미지 로컬화 가이드

## 현재 상태

외부 URL(lh3.googleusercontent.com)에서 이미지를 불러오는 HTML 파일이 **7개**, 총 **30개** 이미지입니다.

---

## 추천 폴더 구조

```
portfolio/
├── images/
│   ├── crossfire/          ← (기존) 프로젝트 메인
│   ├── chrono/
│   ├── justcause/
│   ├── quantum/
│   └── playground/         ← 메인 페이지 실험실 썸네일 (6장)
│       ├── thumb_texteffect.jpg
│       ├── thumb_boostvfx.jpg
│       ├── thumb_loadingeffect.jpg
│       ├── thumb_mission.jpg
│       ├── thumb_uimotion.jpg
│       └── thumb_mercy.jpg
│
├── playground/
│   ├── texteffect/
│   │   ├── index.html
│   │   └── images/         ← 새로 생성
│   │       ├── 01_hero.jpg
│   │       ├── 02_detail.jpg
│   │       ├── 03_node.jpg
│   │       └── 04_mask.jpg
│   ├── boostvfx/
│   │   ├── index.html
│   │   └── images/
│   │       ├── 01_hero.jpg
│   │       ├── 02_detail.jpg
│   │       ├── 03_node.jpg
│   │       ├── 04_frac.jpg
│   │       └── 05_mask.jpg
│   ├── loadingeffect/
│   │   ├── index.html
│   │   └── images/
│   │       ├── 01_hero.jpg
│   │       ├── 02_detail.jpg
│   │       └── 03_node.jpg
│   ├── mission/
│   │   ├── index.html
│   │   └── images/
│   │       ├── 01_hero.jpg
│   │       ├── 02_detail.jpg
│   │       ├── 03_node.jpg
│   │       └── 04_mask.jpg
│   ├── uimotion/
│   │   ├── index.html
│   │   └── images/
│   │       ├── 01_hero.jpg
│   │       ├── 02_detail.jpg
│   │       ├── 03_node.jpg
│   │       └── 04_mask.jpg
│   └── mercy/
│       ├── index.html
│       └── images/
│           ├── 01_hero.jpg
│           ├── 02_detail.jpg
│           ├── 03_node.jpg
│           └── 04_mask.jpg
```

---

## 이미지 목록 (URL → 로컬 파일명 매핑)

### 1. index.html (메인 페이지 — 실험실 썸네일 6장)

| 순서 | 저장 위치 | 설명 | 원본 URL |
|------|-----------|------|----------|
| 1 | `images/playground/thumb_texteffect.jpg` | 텍스트 이펙트 썸네일 | `lh3...KDs9Q=s0` |
| 2 | `images/playground/thumb_boostvfx.jpg` | 부스트 VFX 썸네일 | `lh3...YWMo=s0` |
| 3 | `images/playground/thumb_loadingeffect.jpg` | 로딩 이펙트 썸네일 | `lh3...ScAg=s0` |
| 4 | `images/playground/thumb_mission.jpg` | 미션 완료 썸네일 | `lh3...KLRA=s0` |
| 5 | `images/playground/thumb_uimotion.jpg` | UI 모션 썸네일 | `lh3...QAXA=s0` |
| 6 | `images/playground/thumb_mercy.jpg` | 무기 축복 썸네일 | `lh3...UvA=s0` |


### 2. playground/texteffect/ (4장)

| 순서 | 저장 위치 | alt 텍스트 | 원본 URL |
|------|-----------|-----------|----------|
| 1 | `playground/texteffect/images/01_hero.jpg` | Box Mask (히어로) | `https://lh3.googleusercontent.com/Gh1iSeg1np2FWU68YPxg-lAIzV8yPodr4tzMmD4qluyf-MpmKBkJVG1hofsKb5TlqnjlqUCO4FyC4X72wOve0O1zf0bUmalM7G3kxy9q_8LqOnEE_KDs9Q=s0` |
| 2 | `playground/texteffect/images/02_detail.jpg` | Box Mask | `https://lh3.googleusercontent.com/yTF9nmqRbbMaxmWAOCFOIKbn2loQZVqjtGiLF_d52JRP3Fp4x80b9L-jBSN17TVJENXp2LhHJFyH-TmJHsOwQQ21mlLRukOmbTN2uvv9ITX6B6DEdNbi=s0` |
| 3 | `playground/texteffect/images/03_node.jpg` | Box Mask | `https://lh3.googleusercontent.com/j6J_5dZV9Uku4jcv6vtsiCzOqao0hKrQlJGA-IrINZXUFVzLvMy6pPTZrcND-tUjYdZof3S24-Fwk_rr--yYLcu80tcMh1yu2dxwrb6z0zBd1QVM8k9F1KA=s0` |
| 4 | `playground/texteffect/images/04_mask.jpg` | Box Mask | `https://lh3.googleusercontent.com/wNJSgwL2WoI9gfaEushz82uAZeg_fmR6iyGc-iPwBRKk62-WXql4KTXSBWu5XeMr_qzEE-lJ0A63C0JgFKefJiQz9jLsVCVpMwSBf7vtSBnpqeWGr9xcVp4=s0` |


### 3. playground/boostvfx/ (5장)

| 순서 | 저장 위치 | alt 텍스트 | 원본 URL |
|------|-----------|-----------|----------|
| 1 | `playground/boostvfx/images/01_hero.jpg` | Mosaic Random Flickr (히어로) | `https://lh3.googleusercontent.com/w_a-6AtDErmDYFJCcNgzcBu6pkAIAzvVaBqfTi-7peBI_GzFL3xdaK8Tei5mg5E7xYNJ_g7k7JWwXIvnTG0Fuv6zAs7jJznKp1GF7-eZEdzWJd8JYWMo=s0` |
| 2 | `playground/boostvfx/images/02_detail.jpg` | 랜덤 투명도 | `https://lh3.googleusercontent.com/amJnMObDUPp01G_qnV6lENSJwrdHFFs1ZFpC4Aimxu8mgoc1QMKyO65ee1_33W14vWPvbEZdDFn-OZ3f3p80uQk6I4SxdEouP2jA67n-4jdynzR3nWdm=s0` |
| 3 | `playground/boostvfx/images/03_node.jpg` | 노드 구조 | `https://lh3.googleusercontent.com/8TDxF3xLgzWMjqGNIapgjcu-T1ZmJJ8edYRLfDebnUQdRMdFM7OiAvosEMA7QJo6DvskiggWv74UwBRw7NNZsgtbMTVfBOp8JZg8g84XDDPaXs1FLafh0Q=s0` |
| 4 | `playground/boostvfx/images/04_frac.jpg` | Frac 노드 | `https://lh3.googleusercontent.com/TFe5iFlXok32TTtQFDHAaXulYiqrHJz4Al238HTv83RuecV-R2nqx079wocseUdb0zgRuRCgIjJQLs0qBt8mKV2BGB3bdqtCJ1qK_dVY-jAjGK6b_MAO=s0` |
| 5 | `playground/boostvfx/images/05_mask.jpg` | 마스크 | `https://lh3.googleusercontent.com/xSwJu823AEY0amIcwvnWCH0AaoybpE0ntBg2emhtXGJqXuMlnGe922bf-lNwZG6d5UR2ra_o-SaikZh0DNsQ699Q2E0WiWMFniRFkNDFtIs_1Jtmd2Rqrw=s0` |


### 4. playground/loadingeffect/ (3장)

| 순서 | 저장 위치 | alt 텍스트 | 원본 URL |
|------|-----------|-----------|----------|
| 1 | `playground/loadingeffect/images/01_hero.jpg` | FlipBook Animation (히어로) | `https://lh3.googleusercontent.com/1KAnC174OCTWtbEa7am9KIf5HuozV-TWLCgW-pTRU0Sk9pc9h8pmKHm9YBu_UCRCcP2b7FAHy1f9zHrJsx0rznLDZRIDs6idgMfekDdrIUMuDN0YZLScAg=s0` |
| 2 | `playground/loadingeffect/images/02_detail.jpg` | 상세 | `https://lh3.googleusercontent.com/ai1d0blVr3iOmf5avqvYEAMAfsW1FGCk_YOv4JB7-fl-IHJnqVXR_0U487PErXX6PAjasnI7aqYR3gwQK9o9tJ50eicg6SobZFEsyfDHBHLsvrIrlmGkSg=s0` |
| 3 | `playground/loadingeffect/images/03_node.jpg` | 노드 | `https://lh3.googleusercontent.com/qWvnrj1tJZS_MA-tz_QrPYG5mef2dznZ7fnPZrri-hG-0Xp-xPp3P-ti6SxVLemmoMGWJUJB373kLQuXt9nMA5tiJwLgfCLrP6-7TeEskhTurbEXLORNqA=s0` |


### 5. playground/mission/ (4장)

| 순서 | 저장 위치 | alt 텍스트 | 원본 URL |
|------|-----------|-----------|----------|
| 1 | `playground/mission/images/01_hero.jpg` | Radial Wave (히어로) | `https://lh3.googleusercontent.com/C0GI740Hq94aILxz36s8840FTnGNdyqGQekXaZr-_Hyt-tvDUXHDFxdOBDwas2ldjDx93GxCclQ_WNuAsUafAwaS4Xi0Jvf3j3czyeCjeUEqWHe68GKLRA=s0` |
| 2 | `playground/mission/images/02_detail.jpg` | 상세 | `https://lh3.googleusercontent.com/0-sVExI-VBQZTbtyLhvubJy0K0aSVC5habba8VZ7u3xbgJV96gWGFvxLdusZpqk3yi438Nu4hAglmeiE1g9hgKQaR4pWsCmxCjp2cMLX5i9VQdgwBG1u_7E=s0` |
| 3 | `playground/mission/images/03_node.jpg` | 노드 | `https://lh3.googleusercontent.com/S498qwJH1NMnVVISa8Hh3QVCqGQZlDEnDPjTOVBQOkZbsCtp4QV2U_OvmYFZeqG1vd7yVgnV8veyD43RvTpSZYfOO2S31sx6_E2GjFpsr3tz7PakdcScl8M=s0` |
| 4 | `playground/mission/images/04_mask.jpg` | 마스크 | `https://lh3.googleusercontent.com/tIOtkTdrxs8OyCPa4ww9LeQQW-cIANpDdTQo-CAe4Jq6NTC9ZTvXcT8IiJExNNFN-uzzPTzCQa1HymrNsOm35HI2-mDNN-oCEabN9OKkMbE_SJHh3QQA=s0` |


### 6. playground/uimotion/ (4장)

| 순서 | 저장 위치 | alt 텍스트 | 원본 URL |
|------|-----------|-----------|----------|
| 1 | `playground/uimotion/images/01_hero.jpg` | Interaction Wave (히어로) | `https://lh3.googleusercontent.com/ybIIDtDd1iWdCQWnrkmiCbV7GdhS_wRV7JrZU6SiFiUB0NCiYIOW5FpJWQxcs0QpEub_FdUyuZIqlEJK8K86tu2_3cm4m-Mj81qfO7J4hgGSSM4tv7QAXA=s0` |
| 2 | `playground/uimotion/images/02_detail.jpg` | 상세 | `https://lh3.googleusercontent.com/8N2Y73MI8M0C2mgsRnwRJTeCm9ygPWAEsq-hFx8hCyIDBuH20QOymOf0wlhHTl9aTPxUSrG_WER5YL9J0mZUe2ovUzWPKiuq9_C-J0BMEaVPbXvzCsHhgg=s0` |
| 3 | `playground/uimotion/images/03_node.jpg` | 노드 | `https://lh3.googleusercontent.com/yR76GjKjHtOY_k4GIXLohNdbGGVpdiUnYgS-QVQJ27AKCc8nPkNBLVCr53FGRV1nBT2yvJOFn_TNc1e8wwmgn9PeWajXO4zRwtcXN0yYzrp-lf9qy-cA=s0` |
| 4 | `playground/uimotion/images/04_mask.jpg` | 마스크 | `https://lh3.googleusercontent.com/H52UQdfy_4R6tvZLTKvE7TVuUj9essuIWgFzc8om-G9VDcrL72qhUdSfWKd6fRtPQND5E3vTpVs9FSFdT0FRs0TXcNaD66QfWzqpijWEB-VA80KVbdscmg=s0` |


### 7. playground/mercy/ (4장)

| 순서 | 저장 위치 | alt 텍스트 | 원본 URL |
|------|-----------|-----------|----------|
| 1 | `playground/mercy/images/01_hero.jpg` | Shape Wave (히어로) | `https://lh3.googleusercontent.com/fr3ry9bkUd7x007w5VQZaW4I2XaNV_9sasIMq0DfZt7LE4mp4-BZHzLmHCCFQ7GeUhzfV-8YZZOo9nbBDQK4Bf9zjlIhsIM0cgqInotbsb_z1jH5_t3UvA=s0` |
| 2 | `playground/mercy/images/02_detail.jpg` | 상세 | `https://lh3.googleusercontent.com/lMVdNozyXb48ZvdVp0pH55AZM0u2YxFJEvddiST-5MzBRh5dl66OOidjRjiyW-eUqqLlOyhJjRAgdfF_E-YAHln4wrqf47I9E_uKFoUR2_wNPp6LZgb-dw=s0` |
| 3 | `playground/mercy/images/03_node.jpg` | 노드 | `https://lh3.googleusercontent.com/TlGOA_pKCIYj4LdVUO0F7LOAlvu-xFvpYAAuaAhAgLVf2fOuzXAoXGbdCgubZxQPWSqrkZEnZ0ahUGKnO9nl-hiZmeQZpZiLOgaYNe-M3g1zjUr8iWLa=s0` |
| 4 | `playground/mercy/images/04_mask.jpg` | 마스크 | `https://lh3.googleusercontent.com/POYP0k8qlMkm9CjmQn2B54yyGoEM4ZV1fsOiN4ER0fziWwFdNbHBipH8BwZH8WlCyiI52X1C7XJcXNShd_2_nMgpNejwjT-_MsEiHUbQEFw85SNnvHBm=s0` |

---

## 작업 순서

1. 위 표의 원본 URL을 브라우저에서 열어 이미지를 확인합니다
2. 각 이미지를 위 표의 "저장 위치" 경로에 맞게 폴더를 만들고 저장합니다
3. 저장이 끝나면 저에게 알려주세요 — HTML 파일의 URL을 로컬 경로로 일괄 교체해드리겠습니다

## 참고

- 이미지 형식은 JPG/PNG/WebP 무관 (저장한 형식에 맞춰 HTML 수정 가능)
- 파일명은 위 가이드와 다르게 해도 됩니다 — 알려주시면 맞춰서 교체합니다
- 총 **30장** (썸네일 6장 + 상세 페이지 24장)
