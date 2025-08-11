---
layout: default
title: Moonpie's Blog
---

# ✨ Welcome to Moonpie's Blog
Here’s where I spill thoughts, poems, chaos, and lessons.

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> – {{ post.date | date: "%B %d, %Y" }}
    </li>
  {% endfor %}
</ul>
