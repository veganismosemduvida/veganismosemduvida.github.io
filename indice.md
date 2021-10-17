---
title: Todas as questões
date: 2020-12-13T11:58:42+00:00
author: fernanda
layout: page
permalink: /indice/
---

{% assign sortedPosts = site.posts | sort: 'url' %} 

<div>
  {% for post in sortedPosts %}
    <p class="question-list">
      <a href="{{ post.url }}">{{ post.title }}</a>
    </p>
  {% endfor %}
</div>

![[Foto de dois gatos e um pavão na Quinta das Águias]](/assets/images/quinta_aguias_gatos_pavao.png "Dois gatos e um pavão na Quinta das Águias")

<div class="img-caption">Foto cedida pela <a href="https://www.facebook.com/associacaoquintadasaguias/photos/2762611720497915/">Quinta das Águias</a>.</div>

