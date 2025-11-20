---
layout: page
permalink: /publications/
title: Publications
description: Publications reverse chronological order. Up-to-date information available at <href="https://scholar.google.com/citations?user=mNRvh0EAAAAJ&hl=en">Google Scholar</href>.
nav: true
nav_order: 2

scholar:
  max_authors: 5
  sort_by: year,month
  order: descending,descending # Sort years descending, and within each year, months descending
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

{% bibliography %}

</div>
