---
title: Checklists
permalink: /checklists/
layout: page
---

<div class="checklist-items">
  {% for item in site.checklists %}
    <div class="checklist-item">
      <a href="{{ item.url | relative_url }}">{{ item.title }}</a>
    </div>
  {% endfor %}
</div>
