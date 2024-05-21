---
title: Families in Cambodia
layout: base
pageClass: families-Cambodia
---

<div class="main-content">
  <h1>Families in Cambodia</h1>
  <div class="grid-container">
    {%- for page in collections.Cambodia %}
    <article class="card">
      <a href="{{ page.url }}">
        <img src="/media/{{ page.data.image }}" alt="{{ page.data.imageAlt }}" class="card-image">
        <div class="card-info">
          <h3 class="card-title">{{ page.data.title }}</h3>
        </div>
      </a>
    </article>
    {%- endfor %}
  </div>
</div>


