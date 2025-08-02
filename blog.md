---
layout: page
title: Blog
permalink: /blog/
---

# My Blog Posts

Welcome to my blog where I share my thoughts on AI, technology, and my learning journey.

{% for post in site.posts %}
  <div class="post-preview">
    <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
    <p class="post-meta">{{ post.date | date: "%B %d, %Y" }}</p>
    <p>{{ post.excerpt }}</p>
  </div>
{% endfor %}
