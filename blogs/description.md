---
layout: post
title: Project overview
---

# My project page
Welcome! This is meant to be the place where I write about the personal projects I'm doing right now. You can see some of this in descriptions below: 

<ul>
  {% for post in site.posts %}
    <li>
      <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>