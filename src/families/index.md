---
title: Family 278
layout: base
---
<h1>Pages Tagged with "Toy"</h1>

<ul>
  {% for page in collections.China %}
    <li><a href="{{ page.url }}">{{ page.data.title }}</a></li>
  {% endfor %}
</ul>
<h1>Pages Tagged with "Toy"</h1>
<ul>
  {% for page in collections.India %}
    <li><a href="{{ page.url }}">{{ page.data.title }}</a></li>
  {% endfor %}
</ul>
<div class="grid-container">
{% for page in collections.India %}
        <article class="card">
            <a href="{{ page.url }}">
                <img src="/media/{{ page.data.image }}" alt="{{ page.data.imageAlt }}" class="card-image">
                <div class="card-info">
                    <h3 class="card-title">{{ page.data.title }}</h3>
                    
                </div>
            </a>
        </article>
         {% endfor %}
        </div>
