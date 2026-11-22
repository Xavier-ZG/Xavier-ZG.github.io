---
layout: page
permalink: /publications/
title: Publications
nav: true
nav_order: 2
---


<div class="publications">

<h2>Peer-Reviewed Journal Papers</h2>
{% bibliography --group_by none --query @article %}

<h2>Peer-Reviewed Conference Proceedings</h2>
{% bibliography --group_by none --query @inproceedings %}

<h2>Other Publications</h2>
{% bibliography --group_by none --query @misc %}

</div>
