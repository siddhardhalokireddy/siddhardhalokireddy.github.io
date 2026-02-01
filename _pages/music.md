---
layout: page
title: Music
---

<img src="/assets/images/music.jpg" class="section-cover">

{% for post in site.categories.music %}
<div class="post-card">
  <a href="{{ post.url }}">{{ post.title }}</a>
</div>
{% endfor %}
