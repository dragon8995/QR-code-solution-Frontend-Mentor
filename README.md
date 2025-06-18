# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Frontend Mentor - QR code component solution](#frontend-mentor---qr-code-component-solution)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
    - [Screenshot](#screenshot)
    - [Links](#links)
  - [My process](#my-process)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)
      - [學習 git 使用](#學習-git-使用)
      - [回憶外部 CSS 連結方式](#回憶外部-css-連結方式)
      - [CSS Reset](#css-reset)
      - [糊塗的搞錯語法](#糊塗的搞錯語法)
      - [a 標籤新分頁](#a-標籤新分頁)
      - [引入字型](#引入字型)
    - [Continued development](#continued-development)
    - [Useful resources](#useful-resources)
  - [Author](#author)

## Overview

### Screenshot

![Screenshot](<CleanShot 2025-06-18 at 23.45.31@2x.png>)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [https://dragon8995.github.io/QR-code-solution-Frontend-Mentor/](https://dragon8995.github.io/QR-code-solution-Frontend-Mentor/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

#### 學習 git 使用

- VS Code 內使用從左邊 git 圖示進行 commit 即可
- src: https://code.visualstudio.com/docs/sourcecontrol/overview

#### 回憶外部 CSS 連結方式

```
<head>
    <link rel="stylesheet" type="text/css" href="style.css">
</head>
```

#### CSS Reset

```
/* http://meyerweb.com/eric/tools/css/reset/
   v2.0 | 20110126
   License: none (public domain)
*/

html, body, div, span, applet, object, iframe,
h1, h2, h3, h4, h5, h6, p, blockquote, pre,
a, abbr, acronym, address, big, cite, code,
del, dfn, em, img, ins, kbd, q, s, samp,
small, strike, strong, sub, sup, tt, var,
b, u, i, center,
dl, dt, dd, ol, ul, li,
fieldset, form, label, legend,
table, caption, tbody, tfoot, thead, tr, th, td,
article, aside, canvas, details, embed,
figure, figcaption, footer, header, hgroup,
menu, nav, output, ruby, section, summary,
time, mark, audio, video {
	margin: 0;
	padding: 0;
	border: 0;
	font-size: 100%;
	font: inherit;
	vertical-align: baseline;
}
/* HTML5 display-role reset for older browsers */
article, aside, details, figcaption, figure,
footer, header, hgroup, menu, nav, section {
	display: block;
}
body {
	line-height: 1;
}
ol, ul {
	list-style: none;
}
blockquote, q {
	quotes: none;
}
blockquote:before, blockquote:after,
q:before, q:after {
	content: '';
	content: none;
}
table {
	border-collapse: collapse;
	border-spacing: 0;
}
```

#### 糊塗的搞錯語法

- img 是在.card 標籤下面，打錯結果沒有吃到 CSS

#### a 標籤新分頁

```
<a href="url" target="_blank"></a>
```

#### 引入字型

去 google font 找需要的字型，並在 header 嵌入（註：Outfit 特別好看）

### Continued development

- 字型大小微調
- 行距微調

### Useful resources

- [Font Family: Outfit](https://fonts.google.com/specimen/Outfit) - 非常好看的字型，但還不太會認

## Author

- Website - [William Chao](https://portaly.cc/williamchao?fbclid=PAZXh0bgNhZW0CMTEAAaerTevMpujSEXrKTtOsstjc79oAUPzSrLGwrptKCRV3ELV_C0oWufDTx_qy-w_aem_LtblxF4OwNXsI0iZpvIicw)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
