---
layout: default
title: "Posts"
---

# Posts
<ul>
  {% for post in site.posts %}
  <li>
    <a href="{{ post.url }}">{{ post.title }}</a> - {{ post.date | date: "%Y-%m-%d" }}</a>
  </li>
  {% endfor %}
</ul>

