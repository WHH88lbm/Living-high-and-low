---
title: Families in China
layout: base
pageClass: families-china
---
<header>
  <h1>TOYS IN ASIA</h1>
  <nav>
    <div class="nav-item dropdown">
      <button class="dropbtn">LOCATION</button>
      <div class="dropdown-content">
        <a href="/families/china">China</a>
        <a href="/families/india">India</a>
        <a href="/families/cambodia">Cambodia</a>
      </div>
    </div>
    <div class="nav-item dropdown">
      <button class="dropbtn">INCOME</button>
      <div class="dropdown-content">
        <a href="/families/low">Low</a>
        <a href="/families/high">High</a>
      </div>
    </div>
  </nav>
</header>

<div class="main-content">
  <h1>Families with High Income </h1>
  <ul>
    {% for page in collections.high %}
    <li><a href="{{ page.url }}">{{ page.data.title }}</a></li>
    {% endfor %}
  </ul>
  <div class="grid-container">
    {% for page in collections.high %}
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
</div>

<footer>
  
</footer>