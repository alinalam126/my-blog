---
layout: default
title: My Blog
---
<h1>Latest Posts</h1>

<ul class= "post">
  {% for post in site.posts %}
    <li>
      <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
      <p>{{ post.excerpt }}</p>
    </li>
  {% endfor %}
</ul>