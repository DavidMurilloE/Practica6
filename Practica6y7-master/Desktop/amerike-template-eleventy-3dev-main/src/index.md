---
layout: base.njk
title: Hola Mundo 11ty
---

# David M - Lo QCM Ocurra

[Acerca]({{ '/acerca' | url }})

## Artículos de mi Blog

### Series Netflix 

{% for libro in collections.libros %}

- [{{Documental.data.title}}]({{ Documental.url | url }})

{% endfor %}

### Peliculas de Netflix

{% for serie in collections.series %}

- [{{Pelicula.data.title}}]({{ Pelicula.url | url }})

{% endfor %}

### Documentales de Netflix
{% for serie in collections.series %}

- [{{Serie.data.title}}]({{ Serie.url | url }})

{% endfor %}
### Series de Netflix
