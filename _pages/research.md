---
layout: page
permalink: /research/
title: Research
description: Long description long descroption long description
nav: true
nav_order: 1

# years: [1967, 1956, 1950, 1935, 1905]

---
<!-- _pages/publications.md -->
<div class="publications">

# {%- for y in page.years %}
#  <h2 class="year">{{y}}</h2>
#  {% bibliography -f papers -q @*[year={{y}}]* %}
# {% endfor %}

</div>
