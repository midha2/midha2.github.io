---
layout: page
permalink: /publications/
title: publications
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->
<!-- Each entry in _bibliography/papers.bib sets `pubtype` to full, preprint or short to pick its section. -->

<div class="publications">

<h2 class="bibliography-section">Full papers</h2>

{% bibliography --group_by none --query @*[pubtype=full] %}

{% bibliography --group_by none --query @*[pubtype=preprint] %}

<h2 class="bibliography-section">Lightly peer-reviewed</h2>

{% bibliography --group_by none --query @*[pubtype=short] %}

</div>
