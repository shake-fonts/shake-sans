# Shake Sans

한글과 영문이 한 문장에서 조화롭게 보이는 네오 그로테스크 산세리프 가변 글꼴입니다. [Asta Sans](https://github.com/42dot/Asta-Sans)의 한글과 [Geist](https://github.com/vercel/geist-font)의 영문·숫자를 한 벌로 맞췄고, 9가지 굵기(100–900)와 Condensed·Expanded 너비(75–150)를 제공합니다.

[소개 페이지](https://fonts.shake.st/sans)에서 직접 써 볼 수 있습니다.

## 굵기와 너비

Asta Sans에 없는 한글 Thin과 Black은 기존 굵기를 바탕으로 만들었습니다. Thin은 ExtraLight의 형태에서 획만 가늘게 했고, Black은 ExtraBold의 획을 바깥으로 굵혀 속공간과 자소 사이 간격을 지켰습니다. 영문 Thin과 Black은 Geist를 따릅니다.

Condensed와 Expanded는 너비를 조정하더라도 획 굵기가 일정하게 보이도록 획을 보정했습니다.

## 다운로드

[최신 버전](https://github.com/shake-fonts/shake-sans/releases/latest)

- `static/` 굵기별 TTF — Shake Sans
- `otf/` 굵기별 OTF — Shake Sans
- `condensed/` Condensed TTF·OTF·WOFF2 — Shake Sans (스타일 Condensed, Condensed Bold …)
- `expanded/` Expanded TTF·OTF·WOFF2 — Shake Sans (스타일 Expanded, Expanded Bold …)
- `variable/` 가변 TTF (굵기 100–900 × 너비 75–150) — Shake Sans Variable
- `woff2/` 웹용 WOFF2

Word 같은 오피스 앱에서는 정적 글꼴 사용을 권장합니다.

## 웹폰트

```html
<link rel="stylesheet" href="https://fonts.shake.st/sans/shake-sans.css">
```

```css
body {
  font-family: "Shake Sans", sans-serif;
}
.condensed {
  font-stretch: 75%;
}
.expanded {
  font-stretch: 150%;
}
/* 너비를 75–150% 사이에서 이어서 바꿀 때 */
.variable {
  font-family: "Shake Sans Variable", sans-serif;
  font-stretch: 120%;
}
```

`Shake Sans`는 쓰는 너비(75%·100%·150%)의 파일만 내려받습니다. 너비를 그 사이 값으로 쓰거나 움직이려면 굵기·너비 2축 파일인 `Shake Sans Variable`을 쓰세요.

## 라이선스

[SIL Open Font License 1.1](OFL.txt)에 따라 상업적 용도를 포함해 자유롭게 쓰고, 수정하고, 재배포할 수 있습니다. 글꼴 파일만 따로 판매할 수는 없습니다.

한글·약물·기호는 [Asta Sans](https://github.com/42dot/Asta-Sans) 1.000(42dot), 영문·숫자는 [Geist](https://github.com/vercel/geist-font) 1.800(Vercel, basement.studio)을 바탕으로 합니다. 저작자는 [AUTHORS.txt](AUTHORS.txt)에 있습니다.

만든 사람: Shake · [Shake Studio](https://shake.st)
