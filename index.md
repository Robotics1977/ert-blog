---
layout: default
title: "ERT Blog"
---

# 🧠 ERT Blog
Welcome to my personal blog — where I share robotics progress, engineering insights, and the story behind AstroGear Labs.

---

## 📚 Latest Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a><br>
      <small>{{ post.date | date: "%B %d, %Y" }}</small>
    </li>
  {% endfor %}
</ul>
