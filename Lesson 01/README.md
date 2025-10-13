# Lesson 01 - Introduction

Biz o'rganayotgan tillar:

- **HTML**: Hyper-Text Markup Language (.html)
- **CSS**: Cascading Style Sheet (.css)
- **JavaScript** (.js)
- **React.js** (.jsx)
- **Tailwind CSS** (.html)
- **Markdown** (.md)

## HTML

HTML - saytning strukturasi.

```html
<html>
  <head>
    <title>Mening saytim</title>
    <link rel="stylesheet" href="style.css">
    <script src="script.js" defer></script>
  </head>
  <body>
    <h1>Salom hammaga</h1>
  </body>
</html>
```

- **head**: faqat sayt haqida malumotlar bo'ladi. Va CSS bilan JavaScript ni bog'lash uchun ishlatiladi.
- **body**: sayt ichida ko'rinadigan barcha elementlarni ko'rsatish uchun ishlatiladi.

- **ul** (unordered list): tartibsiz list turi (masalan, mevalar)
- **ol** (ordered list): tartibli list turi (masalan, dars jadvali)

- **target="_blank"**: linkni yangi oynada ('tab'da) ochish usuli

## CSS

CSS - saytning dizayni.

```css
body {
  background-color: black;
}

h1 {
  color: white;
}
```

## JavaScript

JavaScript - saytning funksiyasi.

```js
const olmaNarxi = 5000;

function narxniAniqlash(kg) {
  return olmaNarxi * kg;
}

// Klient 1
narxniAniqlash(5); // 5000 * 5 = 25000
```

## React.js

React - JavaScript ichida HTML yozish

- **jsx**: React fayl formati (.jsx)

```jsx
function Sarlavha() {
  return (
    <h1>Salom hammaga</h1>
  );
}

export default Sarlavha;
```

## Tailwind CSS

Tailwind - HTML ichida CSS yozish.

```html
<body class="bg-black">
  <h1 class="text-white">Salom hammaga</h1>
</body>
```

## Markdown

Markdown - oddiy text dokumenti (bloknot/daftar uchun)

> **README.md**: GitHubda ko'rinishi uchun kerakli fayl nomi

Bu *oddiy* text. Bu yerda **xohlangancha** yozishingiz mumkin. Chunki Markdown da ***turli*** xil formatda textni yozsangiz bo'ladi.

[YouTube kanalim](https://youtube.com)

[Telegram kanalim](https://t.me/telegram)




Do'kon saytini yaratish

- Do'koni ismi ("Saturn") sarlavhada bo'lishi kerak.
- Do'konda 5 ta mahsulot bor (Telefon, Planshet, Monitor, Noutbuk va Klaviatura).
- 5 ta mahsulot list ichida bo'lishi kerak.
- Har bir mahsulotning ismi (h3), narxi (p) va linki (a) bo'lishi kerak.
- Narxini o'zingiz belgilashingiz mumkin ($100 - $2000 atrofida)
- Link addressi: https://uzum-market.com