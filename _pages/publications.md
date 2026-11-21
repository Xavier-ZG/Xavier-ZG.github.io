---
layout: page
permalink: /publications/
title: Publications
nav: true
nav_order: 2
---

<!-- _pages/publications.md：按 CV 的分类显示论文，每类内部按 papers.bib 里的顺序排列 -->

<div class="publications">

<h2>Peer-Reviewed Journal Papers</h2>
{% bibliography --group_by none --query @article %}

<h2>Peer-Reviewed Conference Proceedings</h2>
{% bibliography --group_by none --query @inproceedings %}

<h2>Other Publications</h2>
{% bibliography --group_by none --query @misc %}

</div>
