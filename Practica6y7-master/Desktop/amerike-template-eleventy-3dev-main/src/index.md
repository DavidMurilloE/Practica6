---
layout: base.njk
title: Hola Mundo 11ty
---
![Alt text](<static/img/Foto Perfil.jpg>)
![Alt text](<static/img/Foco de Ideas.gif>)
# Hola que tal, Soy David me Gusta Aprender y Colaborar en Proyectos Chidos 👋

---
Soy un ingeniero en Desarrollo de Sofware en Proceso ... 
--

- 🔭 I’m currently working on ... En Proyectos de Juegos Indies y Desarrollando Proyectos Propios de Apps y Paginas Web.
- 🌱 I’m currently learning ... Estudiando  La Carrera de Ingenieria de Desarrollo de Sorware Interactivo.
- 👯 I’m looking to collaborate on ...Empresa Independiente o de Gobierno.
- 🤔 I’m looking for help with ... Proyectos Varios
- 💬 Ask me about ... Diseño y Planeacion.
- 📫 How to reach me: ...  [_Facebook_](https://www.facebook.com/david.murillo.161?mibextid=ZbWKwL),  [_Twitter_](https://x.com/DavidMurilloE?t=jm5Pr-hTT7q9DI4zXg9fFQ&s=08) o [_Instagram._]()
___
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
