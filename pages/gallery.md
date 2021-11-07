---
layout: page
title: Banco de Imagénes
subtitle: Aquí puedes encontrar todas las gráficas que fueron generadas dentro del proyecto
permalink: /banco/
gallery_path: "assets/img/pexels"
tags: [images,resultados]
---

Como resultado del proyecto se generaron un gran número de gráficos para cada uno de las variables utilizadas ( [ver Diccionario de datos]({% post_url 2021-11-07-diccionario %})).

Cada gráfica tiene un nombre compuesto por la siguiente estructura:

**var_{id}_{tipo de gráfico}.png**
* *id* = Se refiere al id de la variable tomada del [Diccionario de datos]({% post_url 2021-11-07-diccionario %})
* *tipo de gráfico* = Aquí depende del tipo de gráfico creados, el tipo de gráficos son los siguientes:

  - **trend**
  {% include aligner.html images="pexels/var_19_trend.png" %}

  - **scatter**
  {% include aligner.html images="pexels/var_322_scatter.png" %}

  - **scatter_time**

  {% include aligner.html images="pexels/var_80_scatter_time.png" %}

  - **static**

  {% include aligner.html images="pexels/var_79_static.png" %}

  - **map**

  {% include aligner.html images="pexels/var_149_map.png" %}

  - **map_change**

{% include aligner.html images="pexels/var_149_map_change.png" %}

En algunas ocasiones puede existir gráficos en blanco, cuando el tipo de información no permite bajarlo.

[Bajar el Banco de Imágenes](https://github.com/pulsosocialcolombia/pulsosocial-bancoimg/archive/refs/heads/main.zip)
