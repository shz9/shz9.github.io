---
layout: page
permalink: /publications/
title: Publications
description: |
  Publications in reverse chronological order.
  Up-to-date information available at
  <a href="https://scholar.google.com/citations?user=mNRvh0EAAAAJ&hl=en">Google Scholar</a>.
nav: true
nav_order: 2

scholar:
  sort_by: year,month
  order: descending,descending # Sort years descending, and within each year, months descending
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

{% bibliography %}

</div>
