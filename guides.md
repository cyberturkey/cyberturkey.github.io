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

- [Top 6 Privacy Tips](/guides/top-6-privacy-tips/)
- [Types of Info Attackers Can Exploit](/guides/types-of-info-attackers-can-exploit/)
- [Camera Security Guide](/guides/camera-security/)
