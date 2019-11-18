---
layout: post
title:  "Temas en Jekyll"
date:   2019-10-27 20:27:02 +0100
categories: jekyll update
---


Buscando la manera de configurar un tema que no estuviera en la lista oficial de temas de Jekyll para la instalación default de GitHub Pages, encontré una [página de la documentación] que mencionaba que se podría configurar cualquier tema a partir del 2017, con la llave de configuración 'remote_theme': 'usuario/repo'.

Sin embargo, al probar y leer la documentación de varios como jasper2 y Type on Strap, me di cuenta de que aunque puede ser que el tema visual esté soportado (CSS, layouts y JS), la mayoría de los temas se complementa con otros plugins no soportados por la instalación default de GH Pages, por lo que no se pueden instalar directamente, para hacerlo hay que hacer la generación del sitio por separado y subir el sitio generado al repositorio, de preferencia al branch gh-pages.


Consulta [Jekyll docs][jekyll-docs] para tener más información sobre como aprovechar Jekyll.

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
[página de la documentación]: https://github.blog/2017-11-29-use-any-theme-with-github-pages/
