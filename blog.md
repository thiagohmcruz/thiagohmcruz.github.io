---
layout: default
title: Blog
---
<h1>Blog</h1>

<ul>
  {% for post in site.posts %}
    <li>
      <h3><a href="{{ post.url }}">{{ post.title }}</a> - {{ post.date | date: "%B %d, %Y" }}</h3>
    </li>
  {% endfor %}
</ul>