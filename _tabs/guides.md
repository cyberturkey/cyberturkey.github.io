---
layout: page
title: Guides
permalink: /guides/
icon: fas fa-book
layout: page
order: 4
---

This page will hold my guide articles.

<div class="guides-list">
  {% for item in site.guides %}
    <div class="guide-item">
      <a href="{{ item.url | relative_url }}">{{ item.title }}</a>
    </div>
  {% endfor %}
</div>
