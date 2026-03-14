---
layout: default
title: Blog
permalink: /blog/
---

# 💡 Blog

Welcome to my blog! Here I share what I've learned, discoveries, frustrations, and triumphs during my PhD.

<ul class="blog-list">
  {% for post in site.posts %}
    <li>
        <span style="color:#666">[{{ post.date | date: "%Y-%m-%d" }}]</span>
        <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

---