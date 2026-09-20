---
layout: page
permalink: /publications/
title: Publications
description: Publications by categories in reversed chronological order.
suppress_bib_year: true
nav: true
nav_order: 1
custom_js:
  - citations
---

<div class="publications">

<h1>Publications</h1>

{% bibliography -f papers --group_by year --group_order descending %}

<h1>Under Review / Working Papers</h1>

{% bibliography -f preprints --group_by year --group_order descending %}

<h1>Selected Works in Progress</h1>

{% bibliography -f posters --group_by year --group_order descending %}

</div>