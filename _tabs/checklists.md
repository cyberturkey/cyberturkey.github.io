---
layout: page
title: Checklists
permalink: /checklists/
icon: fas fa-list-check
layout: page
order: 3
---

This page will hold my checklist articles.

<div class="checklist-items">
  {% for item in site.checklists %}
    <div class="checklist-item">
      <a href="{{ item.url | relative_url }}">{{ item.title }}</a>
    </div>
  {% endfor %}
</div>

Note: Clicking a link may download the file automatically depending on your browser.
