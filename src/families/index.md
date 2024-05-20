---
title: Home Page
layout: base
pageClass: home
---
<h1>Families in China</h1>
<ul>
{% for page in collections.China %}
<li><a href="{{ page.url }}">{{ page.data.title }}</a></li>
{% endfor %}
</ul>
<ul>
<div class="grid-container">
{% for page in collections.China %}
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
{% endfor %}
</div>
<h1>Families in India</h1>
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
<div class="card-credit"><a href="{{ page.data.creditLink }}">{{ page.data.credit }}</a>
</div>
</article>
{% endfor %}
</div>
<h1>Families in Cambodia</h1>
<ul>
{% for page in collections.Cambodia %}
<li><a href="{{ page.url }}">{{ page.data.title }}</a></li>
{% endfor %}
</ul>
<div class="grid-container">
{% for page in collections.Cambodia %}
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
{% endfor %}
</div>



