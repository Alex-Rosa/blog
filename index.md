---
layout: default
title: Home
---
# Welcome to My Tech Blog

Check out the latest posts below.

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url | relative_url }}) <small>{{ post.date | date: "%B %d, %Y" }}</small>
{% endfor %}