---
layout: page
permalink: /publications/
title: "Publications"
description: Peer-reviewed publications by Dr. Zhiheng Wang, organized chronologically.
nav: true
nav_order: 2
---

## Selected Publications

The following is a list of selected peer-reviewed journal papers by Dr. Zhiheng Wang. Use the search box to filter by keyword, year, or co-author.

<!-- Bibsearch Feature -->
{% include bib_search.liquid %}

<div class="publications">
  {% bibliography -f papers --query @*[selected=true]* %}
</div>
