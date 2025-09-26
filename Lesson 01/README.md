# Lesson 01 - Introduction

Biz shu tillarni o'rganamiz:

- **HTML**: Hyper-Text Markup Language
- **CSS**: Cascading Style Sheet
- **JavaScript**
- **React.js**
- **Tailwind CSS**

## HTML

```html
<html>
  <head>
    <title>Sayt nomi</title>
    <link rel="stylesheet" href="style.css">
    <script src="script.js" defer></script>
  </head>
  <body>
    <h1>Hello world</h1>
  </body>
</html>
```

- **head**: sayt malumotlarni yozish uchun va CSS bilan JavaScript ni bog'lash uchun ishlatiladi.
- **body**: saytda barcha elementlarni ko'rsatish uchun.
- **DOCTYPE**: yangi HTML bilan eski XMLni farqlash uchun.
- **lang="uz"**: sayt tilini belgilash uchun.
- **UTF-8**: xalqaro saytlar standart turi.
- **defer**: HTML yuklashini kutib o'tirib, keyin JavaScript ni yugur.

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

narxniAniqlash(2); // 5000 * 2 = 10000
```

## React.js

React - HTML va JavaScriptning osonlashtirilgan varianti. JavaScript ichida HTML ishlatish.

```jsx
function Sarlavha() {
  return (
    <h1>Hello world</h1>
  );
}
```

- **.jsx**: React fayl formati.

## Tailwind CSS

Tailwind - HTML ichida CSS ishlatish.

```html
<body class="bg-black">
  <h1 class="text-white"></h1>
</body>
```