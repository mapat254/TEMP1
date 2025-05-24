---
layout: default
title: Home
---

# Welcome to My Blog!

Browse the latest posts below:

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}
