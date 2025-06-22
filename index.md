---
layout: home
title: "Inicio"
---

# Bienvenido a mi blog

Este es mi blog personal donde comparto mis pensamientos, experiencias y conocimientos sobre desarrollo web, tecnologia y otros temas que me interesan.

## ultimas publicaciones:

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a> - {{ post.date | date: "%d/%m/%Y" }}
    </li>
  {% endfor %}
</ul>

---

*Gracias por visitar mi blog!*
