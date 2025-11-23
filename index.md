---
layout: default
title: "ERT Blog"
---

# 🧠 ERT Blog
Welcome to my personal blog — where I share anything and everything that apppeals to me.

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
