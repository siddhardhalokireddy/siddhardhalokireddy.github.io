---
layout: page
title: Coding
---

<img src="/assets/images/coding.jpg" class="section-cover">

{% for post in site.categories.coding %}
<div class="post-card">
  <a href="{{ post.url }}">{{ post.title }}</a>
</div>
{% endfor %}
