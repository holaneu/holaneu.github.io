---
layout: default
title: "Home"
---

# Welcome to My Blog

This is the homepage of my blog. Here’s a list of recent posts:

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%B %d, %Y" }}
{% endfor %}
