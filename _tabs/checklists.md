---
layout: page
title: Checklists
permalink: /checklists/
icon: fas fa-list-check
layout: page
order: 3
---

This page will hold my checklist articles.

<ul class="checklist-list">
  {% for item in site.checklists %}
    <li class="checklist-item">
      <a href="{{ item.url | relative_url }}">{{ item.title }}</a>
    </li>
  {% endfor %}
</ul>
