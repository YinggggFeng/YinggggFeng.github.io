---
layout: page
permalink: /research/
title: research
description: Things I think about from time to time
years: [2023]
nav: true
nav_order: 1
---
I have broad interests throughout theoretical computer sceince. Currently, I'm particularly interested in algorithms for massive, high-dimensional, or evolving dataset, with security and privacy considerations.

- One topic that I'm working on is robust streaming algorithms under the <a href="https://arxiv.org/abs/2204.09136">white-box adversarial setting</a>, where a stream is chosen adaptively by an adversary who observes the **entire internal state** of the algorithm at each time step. We showed that nontrivial algorithms are still possible.

<!-- _pages/publications.md -->
<div class="publications">
Followings are my publications and manucripts:
{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>