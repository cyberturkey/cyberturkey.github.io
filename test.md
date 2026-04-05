---
title: Test
layout: page
permalink: /test/
---

## Collections overview

site.guides size: {{ site.guides.size }}

<ul>
  {% for item in site.guides %}
    <li>{{ item.title }} → {{ item.url | relative_url }}</li>
  {% endfor %}
</ul>

site.checklists size: {{ site.checklists.size }}

<ul>
  {% for item in site.checklists %}
    <li>{{ item.title }} → {{ item.url | relative_url }}</li>
  {% endfor %}
</ul>
