---
title: Guides
permalink: /guides/
layout: page
---

<ul>
  {% for item in site.guides %}
    <li><a href="{{ item.url | relative_url }}">{{ item.title }}</a></li>
  {% endfor %}
</ul>
