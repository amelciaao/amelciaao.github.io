---
title: Posty
layout: page
---

<div>
  {% for post in site.posts %}
    <div style="padding:1rem;background-color:#ebebeb;border-radius:0.5rem;">
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
      {{ post.author}}
      <a style="display:block;padding:0.5rem;background-color:#edbee9;border-radius:0.5rem" href="{{ post.url }}">Czytaj dalej</a>
    </div>
  {% endfor %}
</div>
 
