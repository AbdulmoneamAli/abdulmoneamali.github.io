---
layout: page
permalink: /publications/
title: publications
description: selected publications grouped by research area.
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

<h2>Noise-Robust Federated Learning</h2>

{% bibliography --query @*[keywords~=noise-robust-fl] %}

<h2>Personalized System Identification</h2>

{% bibliography --query @*[keywords~=system-identification] %}

</div>
