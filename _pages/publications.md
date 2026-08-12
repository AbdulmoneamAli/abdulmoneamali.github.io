---
layout: page
permalink: /publications/
title: publications
description: Research publications and preprints.
nav: true
nav_order: 2
---

{% comment %}
<div class="publications">

{% bibliography --group_by none %}

</div>
{% endcomment %}

<div class="publications">

<h3 class="pub-area">Noise-Robust & Personalized Federated Learning</h3>

{% bibliography --group_by none --query @*[keywords~=noise-robust-fl] %}

<h3 class="pub-area">Hierarchical & Multi-Task Federated Learning</h3>

{% bibliography --group_by none --query @*[keywords~=hierarchical-fl] %}

<h3 class="pub-area">Personalized System Identification</h3>

{% bibliography --group_by none --query @*[keywords~=system-identification] %}

<h3 class="pub-area">Wireless Communications & Networks</h3>

{% bibliography --group_by none --query @*[keywords~=wireless-networks] %}

</div>
