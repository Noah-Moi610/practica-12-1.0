---
layout: layout-base.njk
title: Noé Moisés Galindo Leal
---

# {{ title }}

## Espero que les guste mi contenido!

Hola, soy estudiante de la universidad de Amerike, estoy estudiando la carrera de ciberseguridad y desde niño me ha fasinado laas aventuras, deportes extremos y las grandes emociones; siempre ando en busca del peligro y la sensación de la adrenalina, quizá la gente lo vea sucida, pero a mi no me importa lo que la gente piense u opine. Esta es mi vida y así la estoy viviendo.

## Articulos de Blog

### Categoría deportes Aereos

{% for aereo in collections.aereo %}

- [{{aereo.data.title}}]({{ aereo.url | url }})

{% endfor %}

### Categoría deportes Terrestres

{% for terrestre in collections.terrestre %}

- [{{terrestre.data.title}}]({{ terrestre.url | url }})

{% endfor %}

### Categoría deportes Acuaticos 

{% for acuatico in collections.acuatico %}

- [{{acuatico.data.title}}]({{ acuatico.url | url }})


{% endfor %}


![Deportes extremos](https://tse3.mm.bing.net/th?id=OIP.Bki_F_bR2wTdP-ljwS5I_gHaEH&pid=Api&P=0&h=180)


![Yo](./static/img/Yo.jpg)
