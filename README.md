# 구름 산스

[배포처 바로가기](https://goorm-sans.goorm.io/)

&nbsp;

## 웹 폰트

사용하는 `font-family`의 이름은 `Goorm Sans`입니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/GoormSans/goorm-sans.css" type="text/css"/>
```

### CSS `@Import`

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/GoormSans/goorm-sans.css');
```

### CSS `@font-face`

```css
@font-face {
  font-family: 'Goorm Sans';
  font-weight: 400;
  font-style: normal;
  font-display: swap;
  src: url('https://cdn.jsdelivr.net/gh/fonts-archive/GoormSans/goorm-sans-regular.woff2') format('woff2'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/GoormSans/goorm-sans-regular.woff') format('woff'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/GoormSans/goorm-sans-regular.otf') format('opentype'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/GoormSans/goorm-sans-regular.ttf') format('truetype');
}
@font-face {
  font-family: 'Goorm Sans';
  font-weight: 500;
  font-style: normal;
  font-display: swap;
  src: url('https://cdn.jsdelivr.net/gh/fonts-archive/GoormSans/goorm-sans-medium.woff2') format('woff2'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/GoormSans/goorm-sans-medium.woff') format('woff'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/GoormSans/goorm-sans-medium.otf') format('opentype'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/GoormSans/goorm-sans-medium.ttf') format('truetype');
}
@font-face {
  font-family: 'Goorm Sans';
  font-weight: 700;
  font-style: normal;
  font-display: swap;
  src: url('https://cdn.jsdelivr.net/gh/fonts-archive/GoormSans/goorm-sans-bold.woff2') format('woff2'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/GoormSans/goorm-sans-bold.woff') format('woff'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/GoormSans/goorm-sans-bold.otf') format('opentype'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/GoormSans/goorm-sans-bold.ttf') format('truetype');
}
```

&nbsp;

## 다이나믹 서브셋

웹폰트의 최적화를 위해 모던 브라우저에서는 글리프를 여러개로 나누어 필요한 부분만 동적으로 파싱하는 다이나믹 서브셋을 제공합니다. 폰트의 용량이 부담된다면 아래 코드를 사용하는 걸 추천합니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/GoormSans/subsets/goorm-sans-dynamic-subset.css" type="text/css"/>
```

### CSS

```css
@import url("https://cdn.jsdelivr.net/gh/fonts-archive/GoormSans/subsets/goorm-sans-dynamic-subset.css");
```

&nbsp;

## font-family

어느 브라우저나 시스템 환경에서도 동일한 폰트가 적용되어야 한다면 아래와 같이 구성하는 걸 추천합니다. `-apple-system`과 `BlinkMacSystemFont`는 맥, `Segoe UI`는 윈도우, `Roboto`는 안드로이드의 기본 폰트입니다.

```css
font-family: "Goorm Sans", -apple-system, BlinkMacSystemFont, "Segoe UI",Roboto, Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
```

&nbsp;

## 라이선스

라이선스는 언제든지 변경될 수 있습니다. 변경사항을 확인하려면 배포처를 방문해 주세요.

```
구름 산스의 지적재산권은 구름이 소유하고 있으며, SIL Open Font License를 따릅니다.
‘구름 산스, 구름 산스 코드’는 모두에게 무료로 제공합니다.
글꼴의 단독 판매 또는 글꼴을 변경하여 상업적 목적을 취하는 것은 제한됩니다.
구름 산스는 사용, 수정, 재배포가 가능하며 모든 파생 작업은 본 라이센스를 따릅니다.
문의사항 : contact@goorm.io
```
