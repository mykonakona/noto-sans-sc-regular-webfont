# noto-sans-sc-regular-webfont

## 简介

自托管在[vercel](https://vercel.com/) 的思源黑体简中，用于博客类个站的加速，字重regular。

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
