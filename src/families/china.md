---
title: Families in China
layout: base
pageClass: families-china
---


<div class="main-content">
  <h1>Families in China</h1>

  <div class="grid-container">
    {%- for page in collections.China %}
    <article class="card">
      <a href="{{ page.url }}">
        <img src="/media/{{ page.data.image }}" alt="{{ page.data.imageAlt }}" class="card-image">
        <div class="card-info">
          <h3 class="card-title">{{ page.data.title }}</h3>
        </div>
      </a>
      <div class="card-credit"><a href="{{ page.data.creditLink }}">{{ page.data.credit }}</a>
      </div>
    </article>
    {%- endfor %}
  </div>
</div>

