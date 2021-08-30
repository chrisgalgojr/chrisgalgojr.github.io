---
layout: page
title: "Blog"
---

Welcome! This is a repository of blog posts I have written. 

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
