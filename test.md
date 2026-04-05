---
title: Test
layout: page
permalink: /test/
---

site.checklists size: {{ site.checklists.size }}

<hr>

{% for item in site.checklists %}
  - {{ item.title }} → {{ item.url }}<br>
{% endfor %}
