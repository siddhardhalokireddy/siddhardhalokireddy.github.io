---
layout: page
title: Music
nav_order: 4
---

<div class="section-hero" style="background-image: url('/assets/images/music.jpg')">
  <h1>Music</h1>
</div>

<div class="section-content">
{% for post in site.categories.music %}
<div class="post-card">

  {% if post.image %}
    <img src="{{ post.image }}" class="post-card-image" alt="{{ post.title }}">
  {% endif %}

  <div class="post-card-content">
    <a href="{{ post.url }}">{{ post.title }}</a>
  </div>

</div>
{% endfor %}
</div>
