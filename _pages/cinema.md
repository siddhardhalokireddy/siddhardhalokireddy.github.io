---
layout: page
title: Cinema
---

{% for post in site.categories.cinema %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}
