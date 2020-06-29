09 🇪🇸 ✍️📺 Videos de Youtube y Vimeo con estilo en Markdown 👨‍🎨👩‍🎨



_Anterior:_ ⏪ [_Listas y Tablas en Markdown_](https://platzi.com/comunidad/listas-y-tablas-con-estilo-en-markdown) ☑️

==«==
---
 
 
> _**" Esta publicación forma parte de una serie denominada: 🇪🇸 ✍️ [Escribe con estilo usando Markdown](https://platzi.com/blog/escribe-con-estilo-usando-markdown "Escribe con estilo usando Markdown"). 👨‍🎨👩‍🎨. Si has llegado aquí sin pasar por allí, te recomiendo visitarla, donde encontraras el índice principal. "**_


==»==
---

## 📺 Incrustar videos de YouTube en Platzi 

Para incrustar o insertar videos, es decir, que se puedan reproducir allí mismo sin que el lector deba ir a otra página, deberemos utilizar la siguiente sintaxis:

==«==
---

`@[youtube]( ZYmIUiK8ZQI|https://www.youtube.com/watch?v=ZYmIUiK8ZQI)`



==» El código anterior producirá:»==
---

  @[youtube]( ZYmIUiK8ZQI|https://www.youtube.com/watch?v=ZYmIUiK8ZQI)


---





## Incrustar videos de Vimeo en Platzi 

==«==
---

`@[vimeo](427943407|https://vimeo.com/427943407/)`


==» El código anterior producirá: »==
---


@[vimeo](128154222|https://vimeo.com/128154222/)


## Enlazar video en Markdown (funciona en GitHub)

Valga la aclaración que con este método **no es necesario descargar la thumbnail**, pues la etiqueta está escrita para que la tome automáticamente de la API de Youtube.




## Youtube API

| Nombre de miniatura      | Tamaño (px) | URL                                              |
|---------------------|-----------|--------------------------------------------------|
| Player Background   | 480x360   | https://i1.ytimg.com/vi/«ID»/0.jpg         |
| Start               | 120x90    | https://i1.ytimg.com/vi/«ID»/1.jpg         |
| Middle              | 120x90    | https://i1.ytimg.com/vi/«ID»/2.jpg         |
| End                 | 120x90    | https://i1.ytimg.com/vi/«ID»/3.jpg         |
| High Quality        | 480x360   | https://i1.ytimg.com/vi/«ID»/hqdefault.jpg |
| Medium Quality      | 320x180   | https://i1.ytimg.com/vi/«ID»/mqdefault.jpg |
| Normal Quality      | 120x90    | https://i1.ytimg.com/vi/«ID»/default.jpg 


 
==«==
---

````[background]: https://i1.ytimg.com/vi/ZYmIUiK8ZQI/0.jpg "background"
[start]: https://i1.ytimg.com/vi/ZYmIUiK8ZQI/1.jpg "start"
[middle]: https://i1.ytimg.com/vi/ZYmIUiK8ZQI/2.jpg "middle"
[end]: https://i1.ytimg.com/vi/ZYmIUiK8ZQI/3.jpg "end"
[hqdefault]: https://i1.ytimg.com/vi/ZYmIUiK8ZQI/hqdefault.jpg "hqdefault"
[mqdefault]: https://i1.ytimg.com/vi/ZYmIUiK8ZQI/mqdefault.jpg "mqdefault"
[default]: https://i1.ytimg.com/vi/ZYmIUiK8ZQI/default.jpg "default"
[urlYoutube]: https://www.youtube.com/watch?v=ZYmIUiK8ZQI "Titulo del video"


[![x][start]][urlYoutube] [![x][middle]][urlYoutube] [![x][end]][urlYoutube] [![x][default]][urlYoutube] [![x][mqdefault]][urlYoutube] [![x][hqdefault]][urlYoutube] [![x][background]][urlYoutube]
````




==» El Código anterior producirá:==
---

[background]: https://i1.ytimg.com/vi/ZYmIUiK8ZQI/0.jpg "background"
[start]: https://i1.ytimg.com/vi/ZYmIUiK8ZQI/1.jpg "start"
[middle]: https://i1.ytimg.com/vi/ZYmIUiK8ZQI/2.jpg "middle"
[end]: https://i1.ytimg.com/vi/ZYmIUiK8ZQI/3.jpg "end"
[hqdefault]: https://i1.ytimg.com/vi/ZYmIUiK8ZQI/hqdefault.jpg "hqdefault"
[mqdefault]: https://i1.ytimg.com/vi/ZYmIUiK8ZQI/mqdefault.jpg "mqdefault"
[default]: https://i1.ytimg.com/vi/ZYmIUiK8ZQI/default.jpg "default"
[urlYoutube]: https://www.youtube.com/watch?v=ZYmIUiK8ZQI "Titulo del video"


[![x][start]][urlYoutube] [![x][middle]][urlYoutube] [![x][end]][urlYoutube] [![x][default]][urlYoutube] [![x][mqdefault]][urlYoutube] [![x][hqdefault]][urlYoutube] [![x][background]][urlYoutube]


## Vimeo API

Lo primero que debemos observar es la ID publica 128154222 y con ella realizamos el llamado a la api para obtener los datos del video, puedes elegir el formato que gustes
 
* [http://vimeo.com/api/v2/video/128154222.json](http://vimeo.com/api/v2/video/128154222.json)
* [http://vimeo.com/api/v2/video/128154222.php](http://vimeo.com/api/v2/video/128154222.php)
* [http://vimeo.com/api/v2/video/128154222.xml](http://vimeo.com/api/v2/video/128154222.xml)
 
Para este ejemplo hemos realizado la llamada al archivo json, y luego de pasarlo por [jsonbeautifier](https://jsonbeautifier.org) obtenemos
---

>````
>[
>  {
>    "id": 128154222,
>    "title": "Lytro Test Video",
>    "description": "A sample video create from a single still photo snapped with the Lytro Illum. Read our full review of the Illum here: http://bit.ly/1EXnxU8  © >David Patiño",
>    "url": "https://vimeo.com/128154222",
>    "upload_date": "2015-05-18 11:22:34",
>    "thumbnail_small": "http://i.vimeocdn.com/video/519177743_100x75.jpg",
>    "thumbnail_medium": "http://i.vimeocdn.com/video/519177743_200x150.jpg",
>    "thumbnail_large": "http://i.vimeocdn.com/video/519177743_640.jpg",
>    "user_id": 5862464,
>    "user_name": "PDNOnline",
>    "user_url": "https://vimeo.com/user5862464",
>    "user_portrait_small": "http://i.vimeocdn.com/portrait/5664890_30x30",
>    "user_portrait_medium": "http://i.vimeocdn.com/portrait/5664890_75x75",
>    "user_portrait_large": "http://i.vimeocdn.com/portrait/5664890_100x100",
>    "user_portrait_huge": "http://i.vimeocdn.com/portrait/5664890_300x300",
>    "stats_number_of_likes": 3,
>    "stats_number_of_plays": 843,
>    "stats_number_of_comments": 0,
>    "duration": 10,
>    "width": 1056,
>    "height": 720,
>    "tags": "Lytro, photography, cameras, technology",
>    "embed_privacy": "anywhere"
>  }
>]
>````
>
> **En la respuesta obtenemos los datos del id interno 519177743 y nos ofrece 3 tamaños de miniatura. Es necesario que el video no sea privado**

==«==
---

````
[![][small]][urlVimeo]
[![][medium]][urlVimeo]
[![][large]][urlVimeo]

[small]: https://i.vimeocdn.com/video/519177743_100x75.jpg "Small 100x75"
[medium]: https://i.vimeocdn.com/video/519177743_200x150.jpg "Medium 200x150"
[large]: https://i.vimeocdn.com/video/519177743_640.jpg "Large 640"
[urlVimeo]: https://vimeo.com/128154222/ "Vimeo"
````


==» El Código anterior producirá:==
---

[![][small]][urlVimeo]
[![][medium]][urlVimeo]
[![][large]][urlVimeo]

[small]: https://i.vimeocdn.com/video/519177743_100x75.jpg "Small 100x75"
[medium]: https://i.vimeocdn.com/video/519177743_200x150.jpg "Medium 200x150"
[large]: https://i.vimeocdn.com/video/519177743_640.jpg "Large 640"
[urlVimeo]: https://vimeo.com/128154222/ "Vimeo"




==«==
---

**_Continúa tu aprendizaje con:_**

* ⏩ [_ASCII Art en Markdown_](https://platzi.com/comunidad/ascii-art-con-estilo-en-markdown) 🔣

==»==
---
[📖](https://platzi.com/comunidad/textos-con-estilo-en-markdown/ "Textos en Markdown")  [📷](https://platzi.com/comunidad/imagenes-con-estilo-en-markdown/ "Imágenes en Markdown") [🎬](https://platzi.com/comunidad/animaciones-con-estilo-en-markdown/ "Animaciones en Markdown") [🍕](https://platzi.com/comunidad/emojis-con-estilo-en-markdown/ "Emojis en Markdown") [🆎](https://platzi.com/comunidad/variables-con-estilo-en-markdown/ "Variables en Markdown") [🔲](https://platzi.com/comunidad/botones-con-estilo-en-markdown/ "Botones en Markdown")  [🌈](https://platzi.com/comunidad/colores-con-estilo-en-markdown/ "Colores en Markdown")  [☑️](https://platzi.com/comunidad/listas-y-tablas-con-estilo-en-markdown/ "Listas y Tablas en Markdown")  [📺](https://platzi.com/comunidad/videos-de-youtube-y-vimeo-con-estilo-en-markdown/ "Videos de Youtube y Vimeo en Markdown")  [🔣](https://platzi.com/comunidad/ascii-art-con-estilo-en-markdown/ "ASCII Art en Markdown")  [➗](https://platzi.com/comunidad/bonus-formulas-matematicas-con-estilo-en-markdown "Bonus: Fórmulas matemáticas en Markdown")


Hecho con el 💚 en el 2K20. 


[⚫](https://github.com/mistersoftware/Escribe-con-estilo-usando-Markdown/blob/master/09-videos-de-toutube-y-vimeo-con-estilo-en-markdown.md "Repositorio de este articulo en GitHub")

