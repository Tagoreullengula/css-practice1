# `08` Rounded Image

Muchos sitios web usan imágenes de perfil redondeadas, ¡una técnica que realmente hace que un sitio web sea más hermoso!

La forma obvia de crear una imagen de perfil redondeada es crear una etiqueta de imagen y aplicar un `border-radius: 100%`. 

El problema con este enfoque es que solo funciona para imágenes cuadradas... Las imágenes de perfil generalmente tienen diferente altura y ancho, no se verán como un círculo, se verán como óvalos:

![Example Image](../../.learn/assets/08-1.png?raw=true)

## 📝 Instrucciones:

1. Usa `border-radius`.

2. Usa las propiedades `width` y `height` para hacer que la imagen sea cuadrada.

3. Además de `border-radius`, tenemos que utilizar también la propiedad `object-fit`, [aquí hay una explicación](https://www.loom.com/share/15186e456dfd4741887997af40325721).

## 💡 Pista:

+ Si la imagen es más grande que su contenedor y quieres centrarla o enfocarte en una zona en particular, puedes utilizar `object-position`.

+ En este artículo puedes leer más [sobre la propiedad object fit](https://css-tricks.com/on-object-fit-and-object-position/).

+ Adicionalmente, puedes [leer la documentación de object-position](https://developer.mozilla.org/en-US/docs/Web/CSS/object-position) y [la documentación de object-fit](https://developer.mozilla.org/en-US/docs/Web/CSS/object-fit).
