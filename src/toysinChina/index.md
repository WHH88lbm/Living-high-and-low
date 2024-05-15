---
title: Toys in China
tags: [collection]
layout: base
---

# {{ title }}
<ul>
  {% for page in collections.china %}
    <li><a href="{{ page.url }}">{{ page.data.title }}</a></li>
  {% endfor %}
</ul>