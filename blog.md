---
layout: page
title: Blog
permalink: /blog
---

<ul>
  {% for post in site.posts %}
    <li>
      <h3><a href="{{ post.url }}">{{ post.title }}</a> - {{ post.date | date: "%B %d, %Y" }}</h3>
    </li>
  {% endfor %}
</ul>