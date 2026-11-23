---
layout: page
title: 詩
permalink: /poem/
---

詩。

<ul>
  {% for post in site.categories.poem %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <span style="color: #828282; font-size: 0.9em;"> - {{ post.date | date: "%Y-%m-%d" }}</span>
    </li>
  {% endfor %}
</ul>
