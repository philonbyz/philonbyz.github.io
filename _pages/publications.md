---
layout: page
title: publications
permalink: /publications/
nav: true
nav_order: 3
---

> `*` indicates papers with authors listed in alphabetical order.

{% include bib_search.liquid %}

<div class="publications">
  {% bibliography --group_by year --query @* %}
</div>
