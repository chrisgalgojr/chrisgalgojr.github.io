---
layout: page
title: "Blog"
---

This is a repository of blog posts I have written concerning topics I found interesting. Welcome!

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
