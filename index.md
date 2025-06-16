---
layout: default
title: "Hamidreza Lolaei"
---

# 👨‍💻 Hamidreza Lolaei

## 🚀 My Projects

A collection of work in simulations, numerical analysis, and more.


<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> – {{ post.date | date: "%Y-%m-%d" }}
    </li>
  {% endfor %}
</ul>


