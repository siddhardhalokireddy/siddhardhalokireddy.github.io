---
layout: page
title: Cinema
nav_order: 5
---

<img src="/assets/images/cinema.jpg" class="section-cover">

{% for post in site.categories.cinema %}
<div class="section-hero" style="background-image: url('/assets/images/cinema.jpg')">
  <h1>Cinema</h1>
</div>

{% endfor %}
