---
layout: page
title: 散文 札記
permalink: /short/
---

這裡收錄了我的散文與詩歌作品。

<ul>
  {% for post in site.categories.short %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <span style="color: #828282; font-size: 0.9em;"> - {{ post.date | date: "%Y-%m-%d" }}</span>
    </li>
  {% endfor %}
</ul>
