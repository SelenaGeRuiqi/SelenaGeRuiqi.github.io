---
layout: page
permalink: /Research/
title: Research
description: Projects/Publications by categories in reversed chronological order.
nav: true
nav_order: 2
---

<!-- _pages/research.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

{% bibliography --group_by year --group_order descending --sort_by year,title --order descending,ascending %}

</div>
