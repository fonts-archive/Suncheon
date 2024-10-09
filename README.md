# 순천체

[배포처 바로가기](https://www.suncheon.go.kr/kr/info/0003/0001/0003/)

&nbsp;

## 웹 폰트

사용하는 `font-family`의 이름은 `Suncheon`입니다.

### HTML

```html
<link
  rel="stylesheet"
  href="https://cdn.jsdelivr.net/gh/fonts-archive/Suncheon/Suncheon.css"
  type="text/css"
/>
```

### CSS `@Import`

```css
@import url("https://cdn.jsdelivr.net/gh/fonts-archive/Suncheon/Suncheon.css");
```

### CSS `@font-face`

```css
@font-face {
  font-family: 'Suncheon';
  font-weight: 400;
  font-style: normal;
  font-display: swap;
  src: url('https://cdn.jsdelivr.net/gh/fonts-archive/Suncheon/Suncheon-Regular.woff2') format('woff2'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/Suncheon/Suncheon-Regular.woff') format('woff'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/Suncheon/Suncheon-Regular.otf') format('opentype'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/Suncheon/Suncheon-Regular.ttf') format('truetype');
}
@font-face {
  font-family: 'Suncheon';
  font-weight: 700;
  font-style: normal;
  font-display: swap;
  src: url('https://cdn.jsdelivr.net/gh/fonts-archive/Suncheon/Suncheon-Bold.woff2') format('woff2'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/Suncheon/Suncheon-Bold.woff') format('woff'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/Suncheon/Suncheon-Bold.otf') format('opentype'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/Suncheon/Suncheon-Bold.ttf') format('truetype');
}
```

&nbsp;

## 다이나믹 서브셋

웹폰트의 최적화를 위해 모던 브라우저에서는 글리프를 여러개로 나누어 필요한 부분만 동적으로 파싱하는 다이나믹 서브셋을 제공합니다. 폰트의 용량이 부담된다면 아래 코드를 사용하는 걸 추천합니다.

### HTML

```html
<link 
  rel="stylesheet"
  href="https://cdn.jsdelivr.net/gh/fonts-archive/Suncheon/subsets/Suncheon-dynamic-subset.css"
  type="text/css"
/>
```

### CSS

```css
@import url("https://cdn.jsdelivr.net/gh/fonts-archive/Suncheon/subsets/Suncheon-dynamic-subset.css");
```

&nbsp;

## font-family

어느 브라우저나 시스템 환경에서도 동일한 폰트가 적용되어야 한다면 아래와 같이 구성하는 걸 추천합니다. `-apple-system`과 `BlinkMacSystemFont`는 맥, `Segoe UI`는 윈도우, `Roboto`는 안드로이드의 기본 폰트입니다.

```css
font-family: "Suncheon", -apple-system, BlinkMacSystemFont, "Segoe UI",
  Roboto, Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
```

&nbsp;

## 라이선스

라이선스는 언제든지 변경될 수 있습니다. 변경사항을 확인하려면 배포처를 방문해 주세요.

```
이용자가 가지는 권리 
1. 온·오프라인 상에 공유 및 이용 : 온·오프라인을 통하여 공유 및 이용 가능 
2. 저작물 변경 : 2차적 저작물로 변경하여 이용 가능 
3. 이 저작물은 영리 목적으로 이용할 수 있습니다. 
저작물 사용 조건 
- 출처 표시 : 저작물의 출처를 표시하셔야 합니다. 
 
※ 공공기관이 후원한다거나 공공기관과 특수한 관계에 있는 것처럼 제 3자가 오인하게 하는 표시를 해서는 안됩니다. 
 
알아야 할 사항 
I. 이용조건의 표시 및 변경 
1. 이용자가 공공누리 저작물 활용시 출처표시를 꼭 해주셔야 합니다. 
2. 공공누리 저작물의 이용조건은 변경될 수 있습니다. 다만 이용자가 이용조건 변경전 사용하셨다면 해당저작물 한해 용도변경 없이 계속 이용할 수 있습니다. 
II. 이용조건의 위반 
1. 이용자가 공공누리 이용조건을 위반할 경우 그 즉시 이용허락이 종료됩니다. 
2. 이용자가 이용조건 위반 후 지속적으로 공공저작물을 이용할 경우 저작권 침해가 성립되므로 형사상, 민사상 책임을 부담 하실 수 있습니다. 
III. 공공기관의 면책 
1. 공공기관은 공공저작물의 정확성이나 지속적인 제공 등을 보장하지 않습니다. 
2. 공공기관 및 그 직원은 이용자가 공공저작물을 이용함으로써 발생할 수 있는 어떠한 손해나 불이익에 대해서도 책임을 지지 않습니다. 
IV. 기타 
1. 이용자가 저작물을 보유하고 있는 공공기관으로부터 별도의 이용허락을 받은 경우 공공누리 조건을 적용하지 않으셔도 됩니다.
```
