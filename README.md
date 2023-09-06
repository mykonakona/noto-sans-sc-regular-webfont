# noto-sans-sc-regular-webfont

## 简介

自托管于[Vercel](https://vercel.com/) 的简中思源黑体，字重Regular，有效提高[我的静态博客](https://mykonakona.github.io/)的网络字体加载速度。

字体文件来自：[google webfont helper](https://gwfh.mranftl.com/)。

## 使用例

```html
<link rel="preload" href="https://webfonts-seven.vercel.app/noto-sans-sc-v36-chinese-simplified_latin-regular.woff2" as="font" type="font/woff2" crossorigin>
```

```css
/* noto-sans-sc-regular - chinese-simplified_latin */
@font-face {
    font-display: optional; /* Check https://developer.mozilla.org/en-US/docs/Web/CSS/@font-face/font-display for other options. */
    font-family: 'Noto Sans SC';
    font-style: normal;
    font-weight: 400;
    src: url('https://webfonts-seven.vercel.app/noto-sans-sc-v36-chinese-simplified_latin-regular.woff2') format('woff2'); /* Chrome 36+, Opera 23+, Firefox 39+, Safari 12+, iOS 10+ */
}

body {
    font-family: 'Noto Sans SC'
}
```
