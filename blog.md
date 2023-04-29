---
layout: page
title: Blog
permalink: /blog
---

<ul>
  {% for post in site.posts %}
    <li>
      <h4 class="post-meta"><a href="{{ post.url }}">{{ post.title }}</a> - {{ post.date | date: "%B %d, %Y" }}</h4>
    </li>
  {% endfor %}
</ul>