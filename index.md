---
layout: default
title: Home
---

# 👩‍🔬 Welcome to My PhD Journey

Hi, I'm Arturo Morales Bugueño, a PhD student in the intersection between **Control Systems** and **Free-Space Optical Communication Systems** at **Eindhoven University of Technology (TU/e)**.  
<!-- My research focuses on _[your topic]_. -->

---

<div class="news">

**Latest News**
<!-- - <b>2026-01-02:</b> Published my new paper “Awesome Title” in [Prestigious Journal].
- <b>2025-11-20:</b> Presented at SuperCool Conference 2025! -->
- <b>2025-09-22:</b> I started my PhD at Eindhoven University of Technology (TU/e).

</div>

Want more details? [Check out my Blog →](./blog.html)
```

---

### 7. `blog.md` (Blog Page)

```markdown blog.md
---
layout: default
title: Blog
permalink: /blog.html
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

---

### 8. `_posts/2024-06-14-lesson-learned.md` (Sample Blog Post)

```markdown _posts/2024-06-14-lesson-learned.md
---
layout: default
title: What I Learned About Literature Reviews
date: 2024-06-14
---

# What I Learned About Literature Reviews

Today, I learned that approaching literature reviews systematically saves a huge amount of time:

- Use a citation manager!
- Keep notes about each paper you read.
- Make summaries for your future self.

And yes, you can write equations:

Inline: $y = mx + b$

Block:

$$\int_{-\infty}^{\infty} e^{-x^2} dx = \sqrt{\pi}$$

Happy researching!