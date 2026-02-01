---
layout: page
title: Music
---

<div class="section-hero" style="background-image: url('/assets/images/music.jpg')">
  <h1>Music</h1>
</div>

<div class="section-content">
  {% for post in site.categories.music %}
    <div class="post-card">
      <a href="{{ post.url }}">{{ post.title }}</a>
    </div>
  {% endfor %}
</div>
