---
title: Posty
layout: page
---

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
      {{ post.author}}
    </li>
  {% endfor %}
</ul>
 
