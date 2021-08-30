---
layout: page
title: "Blog"
---

Welcome! This is a repository for blog posts that I have written. 

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
