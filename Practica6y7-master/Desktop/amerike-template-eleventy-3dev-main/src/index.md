---
layout: base.njk
title: Hola Mundo 11ty
---

# David M - Lo QCM Ocurra

- Primavera
- Verano
- Otoño
- Invierno

[Acerca]({{ '/acerca' | url }})

## Artículos de mi Blog

### Series Netflix 

{% for libro in collections.libros %}

- [{{libro.data.title}}]({{ libro.url | url }})

{% endfor %}

### Peliculas de Netflix

{% for serie in collections.series %}

- [{{serie.data.title}}]({{ serie.url | url }})

{% endfor %}

### Documentales de Netflix
