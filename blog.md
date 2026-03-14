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
      <a href="{{ post.url }}">{{ post.title }}</a>
      <span style="color:#666;font-size:0.9em">({{ post.date | date: "%Y-%m-%d" }})</span>
    </li>
  {% endfor %}
</ul>
```
> **Note:** Using `permalink: /blog/` makes the page accessible at `/blog/` (which is modern and preferred).

---