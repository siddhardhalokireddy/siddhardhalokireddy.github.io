---
layout: page
title: Books
---

<div class="section-hero" style="background-image: url('/assets/images/books.jpg')">
  <h1>Books</h1>
</div>

<div class="section-content">
  {% for post in site.categories.books %}
    <div class="post-card">
      <a href="{{ post.url }}">{{ post.title }}</a>
    </div>
  {% endfor %}
</div>
