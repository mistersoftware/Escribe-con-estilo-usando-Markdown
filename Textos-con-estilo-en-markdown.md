>1. 📖 [Textos](https://platzi.com/comunidad/textos-con-estilo-en-markdown/ "Textos en Markdown") 
>1. 📷 [Imágenes](https://platzi.com/comunidad/imagenes-con-estilo-en-markdown/ "Imágenes en Markdown") 
>1. 🎬 [Animaciones](https://platzi.com/comunidad/animaciones-con-estilo-en-markdown/ "Animaciones en Markdown") 
>1. 🍕 [Emojis](https://platzi.com/comunidad/emojis-con-estilo-en-markdown/ "Emojis en Markdown") 
>1. 🆎 [Variables](https://platzi.com/comunidad/variables-con-estilo-en-markdown/ "Variables en Markdown") 
>1. 🔲 [Botones](https://platzi.com/comunidad/botones-con-estilo-en-markdown/ "Botones en Markdown") 
>1. 🌈 [Colores](https://platzi.com/comunidad/colores-con-estilo-en-markdown/ "Colores en Markdown") 
>1. ☑️ [Listas y Tablas](https://platzi.com/comunidad/listas-y-tablas-con-estilo-en-markdown/ "Listas y Tablas en Markdown") 
>1. 📺 [Videos de Youtube y Vimeo](https://platzi.com/comunidad/videos-de-youtube-y-vimeo-con-estilo-en-markdown/ "Videos de Youtube y Vimeo en Markdown") 
>1. 🔣 [ASCII Art](https://platzi.com/comunidad/ascii-art-con-estilo-en-markdown/ "ASCII Art en Markdown") 
>1. ➗ [Bonus: Fórmulas matemáticas](https://platzi.com/comunidad/bonus-formulas-matematicas-con-estilo-en-markdown "Bonus: Fórmulas matemáticas en Markdown") 





_Anterior:_ ⏪ [_Escribe con estilo usando Markdown👨‍🎨👩‍🎨_](https://platzi.com/blog/escribe-con-estilo-usando-markdown "Escribe con estilo usando Markdown")


==«==
---
 
 
> _**" Esta publicación forma parte de una serie denominada: 🇪🇸 ✍️ [Escribe con estilo usando Markdown](https://platzi.com/blog/escribe-con-estilo-usando-markdown "Escribe con estilo usando Markdown"). 👨‍🎨👩‍🎨. Si has llegado aquí sin pasar por allí, te recomiendo visitarla, donde encontraras el índice principal. "**_


==»==
---

## 📖 Textos

Markdown es una forma de diseñar texto en la web, donde tú controlas la visualización del documento; resaltando palabras en **negrita** o _cursiva_, agregando 👨‍🚀[emojis](https://platzi.com/comunidad/emojis-y-mas-emojis-con-estilo-en-markdown/)🚀, imágenes, videos, creando listas o tablas. Te recomiendo antes de comenzar ir a [StackEdit](https://stackedit.io/app#)  un editor de Markdown en línea que te facilitara seguir esta guía.


==«==
---
 
 
> _**" Markdown es muy utilizado en la industria de la tecnología por su versatilidad y sencillez. Puedes usarlo en [Slack](https://platzi.com/clases/slack/) y es el lenguaje de marcado por defecto en la documentación de los proyectos en [Git-hub](https://guides.github.com/features/mastering-markdown/).  "**_



==»==
---


Markdown es utilizado en Platzi para el blog, los tutoriales, el foro, los comentarios, tanto en las preguntas como en las respuestas. Dentro de Platzi, el único espacio donde no podrás utilizar Markdown es en los marcadores. (Por lo menos así ocurre hasta la fecha actual 2020)

## Citas

Las citas se inician con el símbolo >. También se suele colocar en cursiva el párrafo entre comillas y en el renglón siguiente el autor de la cita. Algunas implementaciones de Markdown eliminan algunas ciertas para evitar inyección de código Sql, aquí recuperamos los espacios arriba y abajo de la cita usando un renglón con texto resaltado  (cualquier texto debe servir) y seguido un renglón contres guiones al medio, el cual convierte en encabezado el renglón superior y proporciona los espacios perdidos.

==«==
---


````> _**“ Los hombres sabios hablan porque tienen algo que decir; los necios porque tienen que decir algo. ”**_`
`>>Platón````


==» El código anterior producirá: »==
---

>  _**“ Los hombres sabios hablan porque tienen algo que decir; los necios porque tienen que decir algo.  ”**_
> Platón.


## Enlaces
Los enlaces se pueden insertar copiando y pegando la URL completa (no recomendado por falta de legibilidad) o siguiendo la siguiente regla: El texto alternativo para el enlace entre corchetes cuadrados seguido de la URL dentro de paréntesis.


==«==
---

`http://platzi.com – enlace creado de forma automática!`
`[Platzi](http://platzi.com)`


==» El código anterior producirá: »==
---

http://platzi.com – enlace creado de forma automática!

[Platzi](http://platzi.com)

## Encabezados
Para usar la etiqueta de encabezados, deberás iniciar la línea de texto con dos caracteres ##, así:


==«==
---

`## Este es un encabezado`


==» El código anterior producirá: »==
---

## Este es un encabezado
> 

En Platzi la etiqueta H1 se encuentra reservada por el sistema para mantener una correcta estructura semántica. Rara vez necesitarás encabezados diferentes al H2.

## Etiquetas para dar énfasis

Las etiquetas de énfasis, permiten resaltar parte del texto sin obligar un salto de línea.

==«==
---
* `*Este texto aparecerá en cursiva*`
 `_Este texto también aparecerá en cursiva_`
 `**Este texto aparecerá en negrilla**`
 `__Este texto también aparecerá en negrilla__`
 `~~Este texto aparecerá tachado~~`
 `_**Puedes** combinarlos_`
 `También puedes ==resaltarlos==`


==» El código anterior producirá: »==
---


* *Este texto aparecerá en cursiva*
 _Este texto también aparecerá en cursiva_
 **Este texto aparecerá en negrilla**
 __Este texto también aparecerá en negrilla__
 ~~Este texto aparecerá tachado~~
 _**Puedes** combinarlos_
  También puedes ==resaltarlos==
 

## Separadores o saltos de línea

Para incluir una espacio de separación entre párrafos deberás, párrafos usar un doble salto de línea. Cuando deseas incluir una línea de separación puedes intentar con tres guiones al medio seguidos.

==«==
---


`Renglón anterior.`
`---`
`Renglón siguiente.`


==» El código anterior producirá: »==
---

==«==
---
Renglón anterior.
---
Renglón siguiente.


==«==
---

`Renglón anterior.`
`==»==`
`---`
`Renglón siguiente. `


==» El código anterior producirá: »==
---



Renglón anterior.
==»==
---
Renglón siguiente. 



![Imgur](https://i.imgur.com/X2TrK4G.jpg) 
>## Metodo alternativo
>**Si la etiqueta anterior deja una separación muy pequeña, intenta utilizando alguna de estas dos imágenes siguientes. Elige la que mejor te funcione.**
>==«==
>---
>Salto de línea (insertando imagen en blanco)
>Renglón anterior
`![Imgur](https://i.imgur.com/X2TrK4G.jpg)`
Renglón medio
`![Imgur](https://i.imgur.com/EG1jOdW.jpg)`
Renglón siguiente
>
>==» El código anterior producirá: »==
>---
>Renglón anterior. (Este texto se incluye como referencia para medir el tamaño del separador)
![Imgur](https://i.imgur.com/EG1jOdW.jpg)Renglón medio
![Imgur](https://i.imgur.com/EG1jOdW.jpg)
Renglón siguiente
O también puedes usar esta otra técnica
--

==«==
---

Renglón anterior.
`![url1](https://via.placeholder.com/1x1/f6f6f6/f6f6f6?text=+)`
Renglón siguiente. 


==» El código anterior producirá: »==
---
Renglón anterior.
![url1](https://via.placeholder.com/1x1/f6f6f6/f6f6f6?text=+)
Renglón siguiente. 


## Sintaxis para incluir código
==«==
---

\`Una sola línea de código\`


==» El código anterior producirá: »==
---


`Una sola línea de código`


También puedes incrustar bloques de código de varias líneas: 

==«==
---
````
\````javascript
function fancyAlert(arg) {

    if(arg) {

    $.facebox({div:'#foo'})

    }
}
\````
````

==» El código anterior producirá: »==
---


````javascript
function  fancyAlert(arg) {
    if(arg) {
    $.facebox({div:'#foo'})
    }
}
````

## Escapar caracteres

==«==
---

Para escapar caracteres deberás usar el símbolo \ (barra invertida) justo antes del carácter que se quiere escapar.

`- [ ] \(Si vas a incluir paréntesis después de corchetes cuadrados) será necesario escapar el primer paréntesis`


==» El código anterior producirá: »==
---


 - [ ] \(Si vas a incluir paréntesis después de corchetes cuadrados) será necesario escapar el primer paréntesis.

**Será necesario hacer esto cuando quieras que alguno de los siguientes caracteres de control sea mostrado en el documento.**

```
\  barra invertida
`  tilde invertida
*  asterisco
_  guión bajo
#  numeral o almohadilla o gato (o como lo llames 😉)
+  símbolo de suma
-  guión
.  punto
!  exclamación
{} llaves
[] corchetes
() paréntesis
```  






==«==
---



Para evitar que la creación automática de enlaces, deberás escapar parte de sus caracteres así:

`https\:/[]()/example.com/`

==» El código anterior producirá: »==
---
https\:/[]()/example.com/


==«==
---

**_Continúa tu aprendizaje con:_**

* ⏩ [_Imágenes en Markdown_](https://platzi.com/comunidad/imagenes-con-estilo-en-markdown "Imágenes en Markdown") 📷

==»==
---

[📖](https://platzi.com/comunidad/textos-con-estilo-en-markdown/ "Textos en Markdown")  [📷](https://platzi.com/comunidad/imagenes-con-estilo-en-markdown/ "Imágenes en Markdown") [🎬](https://platzi.com/comunidad/animaciones-con-estilo-en-markdown/ "Animaciones en Markdown") [🍕](https://platzi.com/comunidad/emojis-con-estilo-en-markdown/ "Emojis en Markdown") [🆎](https://platzi.com/comunidad/variables-con-estilo-en-markdown/ "Variables en Markdown") [🔲](https://platzi.com/comunidad/botones-con-estilo-en-markdown/ "Botones en Markdown")  [🌈](https://platzi.com/comunidad/colores-con-estilo-en-markdown/ "Colores en Markdown")  [☑️](https://platzi.com/comunidad/listas-y-tablas-con-estilo-en-markdown/ "Listas y Tablas en Markdown")  [📺](https://platzi.com/comunidad/videos-de-youtube-y-vimeo-con-estilo-en-markdown/ "Videos de Youtube y Vimeo en Markdown")  [🔣](https://platzi.com/comunidad/ascii-art-con-estilo-en-markdown/ "ASCII Art en Markdown")  [➗](https://platzi.com/comunidad/bonus-formulas-matematicas-con-estilo-en-markdown "Bonus: Fórmulas matemáticas en Markdown")

Hecho con el 💚 en el 2K20. 

[⚫](https://drive.google.com/file/d/1UKRHMFcB89yyflMAmgsyKWLuZ5wz12bs/view?usp=sharing  "Código fuente de esta página")
