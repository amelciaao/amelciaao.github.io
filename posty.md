---
title: Posty
layout: page
#posts: {{ page.post }} 
---

**Oto lista postów**

{% for post in posts %}
  <div class="post">
    <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
    <p class="date">{{ post.published_at }}</p>
    <p class="author">{{ post.author }}</p>
    <p class="excerpt">{{ post.excerpt }}</p>
  </div>
{% endfor %}
