---
layout: default
title: Writing
permalink: /writing/
---

## here
<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## Devolab
<ul class="posts">
  {% for post in site.data.devolab_posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
  <a href="http://devosoft.org/author/mmore500/">[all Devolab posts]</a>
</ul>