---
layout: default
title: Wellness Guide 
---

# Welcome to my Wellness Blog

This is the homepage of my new blog. Here are my latest posts:

<ul>
{% for post in site.posts %}
  <li><a href="{{ post.url }}">{{ post.title }}</a> - {{ post.date | date: "%Y-%m-%d" }}</li>
{% endfor %}
</ul>
