---
layout: default
title: Rajesh Potlia
---

# Welcome
Hi, I'm **Rajesh Potlia**, a PhD student in Astronomy. My research focuses on astrophysical simulations and machine learning in cosmology.

[Read more about me](about.md)

# Latest Blog Post
{% for post in site.posts limit:1 %}
- [{{ post.title }}]({{ post.url }}) — {{ post.date | date_to_string }}
{% endfor %}
