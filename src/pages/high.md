---
title: Families in China
layout: base
pageClass: families-china
---

<div class="main-content">
  <h1>Families with High Income </h1>
  <div class="grid-container">
    {%- for page in collections.high %}
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