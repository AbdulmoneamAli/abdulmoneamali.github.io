---
layout: page
permalink: /publications/
title: publications
description: Publications grouped by research area.
nav: true
nav_order: 2
---

<div class="publications">

<h2>Noise-Robust & Personalized Federated Learning</h2>

{% bibliography --query @*[keywords~=personalized-fl] %}

<h2>Hierarchical & Multi-Task Federated Learning</h2>

{% bibliography --query @*[keywords~=hierarchical-fl] %}

<h2>Personalized System Identification</h2>

{% bibliography --query @*[keywords~=system-identification] %}

<h2>Wireless Communications & Networks</h2>

{% bibliography --query @*[keywords~=wireless-networks] %}

</div>
