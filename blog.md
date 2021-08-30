---
layout: page
title: "Blog"
---

Welcome! This is the repository for my blog posts. Enjoy reading! 

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
