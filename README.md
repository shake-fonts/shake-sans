# Shake Sans

Shake Sans는 [Asta Sans](https://github.com/42dot/Asta-Sans)의 한글과 [Geist](https://github.com/vercel/geist-font)의 라틴·숫자를 바탕으로 한 한글 Sans-Serif 글꼴입니다. 9가지 굵기(100–900)와 Condensed·Expanded 너비(75–150), Variable Font를 제공합니다.
자세한 내용은 [소개 페이지](https://fonts.shake.st/sans)에서 확인하세요.

Asta Sans에 없는 한글 Thin과 Black은 기존 굵기를 바탕으로 확장했습니다. Thin은 ExtraLight의 형태는 그대로 둔 채 획만 가늘게 했고, Black은 ExtraBold의 획을 바깥으로 굵히면서 속공간과 초성·중성·종성 사이 간격을 그대로 유지했습니다. 라틴 Thin과 Black은 Geist의 굵기를 따릅니다.

Condensed와 Expanded는 너비를 줄이거나 늘려도 세로획 굵기가 달라지지 않도록, 다른 굵기에서 획 두께를 가져와 보정했습니다. 한글은 가로획 굵기와 획이 맞닿는 부분까지 그대로 유지했습니다.

## 다운로드

[최신 버전](https://github.com/shake-fonts/sans/releases/latest)

- `static/` 굵기별 TTF — Shake Sans
- `otf/` 굵기별 OTF — Shake Sans
- `variable/` 가변 TTF (굵기 100–900 × 너비 75–150) — Shake Sans Variable
- `condensed/` Condensed 정적 TTF·OTF·WOFF2 — Shake Sans (스타일 Condensed, Condensed Bold …)
- `expanded/` Expanded 정적 TTF·OTF·WOFF2 — Shake Sans (스타일 Expanded, Expanded Bold …)
- `woff2/` 웹용 WOFF2

정적과 가변은 이름이 달라 함께 설치해도 됩니다. Word 같은 오피스 앱에서는 정적 글꼴(`static/`, `otf/`)을 쓰세요.

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

`Shake Sans`는 너비 75%·100%·150% 중 쓰는 너비의 파일만 받고, `Shake Sans Variable`은 굵기·너비 2축 파일을 받습니다.

## 라이선스

[SIL Open Font License 1.1](OFL.txt)에 따라 상업적 용도를 포함해 자유롭게 사용하고 수정 및 재배포할 수 있습니다. 단, 글꼴 파일 자체만을 판매할 수는 없습니다.

한글·약물·기호는 [Asta Sans](https://github.com/42dot/Asta-Sans) 1.000(42dot), 라틴·숫자는 [Geist](https://github.com/vercel/geist-font) 1.800(Vercel, basement.studio)을 기초로 합니다. 저작자는 [AUTHORS.txt](AUTHORS.txt)에 있습니다.

만든 사람: Shake · [Shake Studio](https://shake.st)
