---
title: Home Page
layout: base
pageClass: home
---
<h1>Families in China</h1>
<ul>
{% for page in collections.China %}
<li><a href="{{ family-42.md }}">{{ page.data.title }}</a></li>
{% endfor %}
</ul>
<ul>
<div class="grid-container">
{% for page in collections.China %}
<article class="card">
<a href="{{ family-184.md }}">
<img src="/media/{{ page.data.image }}" alt="{{ page.data.imageAlt }}" class="card-image">
<div class="card-info">
<h3 class="card-title">{{ page.data.title }}</h3>
</div>
</a>
</article>
{% endfor %}
</div>
<h1>Families in India</h1>
<ul>
{% for page in collections.India %}
<li><a href="{{ family-166.md }}">{{ page.data.title }}</a></li>
{% endfor %}
</ul>
<div class="grid-container">
{% for page in collections.India %}
<article class="card">
<a href="{{ family-278,md }}">
<img src="/media/{{ page.data.image }}" alt="{{ page.data.imageAlt }}" class="card-image">
<div class="card-info">
<h3 class="card-title">{{ page.data.title }}</h3>
</div>
</a>
</article>
{% endfor %}
</div>
<h1>Families in Cambodia</h1>
<ul>
{% for page in collections.Cambodia %}
<li><a href="{{ family-38.md }}">{{ page.data.title }}</a></li>
{% endfor %}
</ul>
<div class="grid-container">
{% for page in collections.Cambodia %}
<article class="card">
<a href="{{ family-41.md }}">
<img src="/media/{{ 41.jpg }}" alt="{{ page.data.imageAlt }}" class="card-image">
<div class="card-info">
<h3 class="card-title">{{ page.data.title }}</h3>
</div>
</a>
</article>
{% endfor %}
</div>


