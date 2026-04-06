---
title: Guides
permalink: /guides/
layout: page
---

<div class="guides">
  {% for item in site.guides %}
    <div class="guide-item">
      <a href="{{ item.url | relative_url }}">{{ item.title }}</a>
    </div>
  {% endfor %}
</div>
