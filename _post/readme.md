---
layout: post
title:  "Welcome to Jekyll!"
---

## the readme for 'post' directory

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
