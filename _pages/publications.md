---
layout: page
permalink: /publications/
title: Publications
description: 
years: [2021, 2019]
nav: true
---

<!-- [[Conference papers](#conference-papers)] | [[Journal papers](#journal-papers)] -->


#### Papers

<div class="publications">

{% for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>