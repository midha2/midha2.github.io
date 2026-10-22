---
layout: page
permalink: /publications/
title: publications
description: Grouped by how much peer review each work has had, most recent first.
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->
<!-- Each entry in _bibliography/papers.bib sets `pubtype` to full, short or preprint to pick its section. -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

{% comment %}
Uncomment once there is a full paper (pubtype = {full}) in papers.bib.

<h2 class="bibliography-section">Full papers</h2>
<p class="text-muted">Peer-reviewed conference and journal papers.</p>

{% bibliography --group_by none --query @*[pubtype=full] %}
{% endcomment %}

<h2 class="bibliography-section">Posters, demos &amp; short papers</h2>
<p class="text-muted">Lightly peer-reviewed: accepted through a poster, demo or extended-abstract track.</p>

{% bibliography --group_by none --query @*[pubtype=short] %}

<h2 class="bibliography-section">In preparation</h2>
<p class="text-muted">Not yet peer-reviewed.</p>

{% bibliography --group_by none --query @*[pubtype=preprint] %}

</div>
