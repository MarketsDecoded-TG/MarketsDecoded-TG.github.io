---
title: Home
---

# Thomas George — Research & Articles

Welcome to my research site. Here are my latest posts:

<ul>
{% for post in site.posts %}
  <li>
    <a href="{{ post.url }}">{{ post.date | date: "%Y-%m-%d" }} — {{ post.title }}</a>
  </li>
{% endfor %}
</ul>
