---
title: Test
layout: page
permalink: /test/
---

site.checklists size: {{ site.checklists.size }}

<ul>
  {% for item in site.checklists %}
    <li>{{ item.title }} → {{ item.url | relative_url }}</li>
  {% endfor %}
</ul>
