---
layout: page
permalink: /publications/
title: Publications
description: Check the full publications <a href="https://scholar.google.com.hk/citations?user=7QxkToIAAAAJ&hl=en"><b>here</b></a>
years: [2022,2021,2020,2019,2018,2017,2015]
nav: true
---

<div class="publications">

{% for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
