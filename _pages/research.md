---
layout: page
permalink: /research/
title: research
description: Things I think about from time to time
years: [2024, 2023]
nav: false
nav_order: 1
---

<!-- _pages/publications.md -->
<div class="publications">
Followings are my publications and manucripts:
{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>