---
layout: default
title: Blog
---

## Blog
{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }}) — {{ post.date | date_to_string }}
{% endfor %}
