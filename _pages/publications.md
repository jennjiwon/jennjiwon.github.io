---
layout: page
permalink: /publications/
title: in progress
description: *Oh, Ji Won* & Hong, Seok Kyeong. Confessions of a Koreaboo
years:
nav: true
---

<div class="publications">

{% for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>

---

*Oh, Ji Won* & Hong, Seok Kyeong. Confessions of a Koreaboo

---
