---
layout: page
title: Cinema
---

<img src="/assets/images/cinema.jpg" class="section-cover">

{% for post in site.categories.cinema %}
<div class="post-card">
  <a href="{{ post.url }}">{{ post.title }}</a>
</div>
{% endfor %}
