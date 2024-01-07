# `04.1` Combined Rules

Los archivos CSS ocupan espacio en tu servidor y también tardan en descargarse (como todo); es otro documento de texto que el navegador debe descargar antes de mostrar la página, por lo que es importante mantener el documento CSS lo más pequeño posible.

Una forma de hacerlo es combinando varias propiedades en una, como con `border`:

```css
border-color: black;
border-style: solid;
border-width: 1px;
```

Las propiedades de border se pueden consolidar en una sola línea así:

```css
border: black 1px solid;
```

## 📝 Instrucciones:


1. Combina las 4 reglas de padding en una sola utilizando la regla `padding`.

2. Combina todas las reglas de background en una sola línea usando la regla `background`.

*Las propiedades `background-position` y `background-size` pueden usar el mismo tipo de datos por lo que entrarán en conflicto, así que en vez de separar estas propiedades con un **espacio**, debes separarlas con una barra `/` de esta forma:*

```css
background: 50px / cover
```

Donde el valor de la izquierda de la barra `/` es la propiedad `background-position` y la derecha es el `background-size`.

## 💡 Pista:

- Cómo usar el background: https://www.w3schools.com/cssref/css3_pr_background.php

- Cómo usar el padding: https://www.w3schools.com/css/css_padding.asp
