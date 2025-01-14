---
layout: about
title: about
years: [2024, 2023]
permalink: /
subtitle: 


profile:
  align: right
  image: me.jpg
  image_circular: false # crops the image to make it circular
  address: >

news: false  # includes a list of news items
latest_posts: false # includes a list of the newest posts
selected_papers: false # includes a list of papers marked as "selected={true}"
social: true  # includes social icons at the bottom of the page
---

Hi! 

I am a fourth-year undergraduate student at <a href='https://www.cs.cmu.edu/'>School of Computer Science, Carnegie Mellon University</a>. I will be starting as a PhD student at MIT in Fall 2024.

My academic interest is theoretical computer science in general. Currently, I'm particularly interested in algorithms for massive or high-dimensional data.



&nbsp;

<!-- _pages/publications.md -->
<div class="publications">
{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>