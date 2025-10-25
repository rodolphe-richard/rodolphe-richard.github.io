---
layout: page
permalink: /preprints/
title: preprints
description: my latest preprints
nav: true
nav_order: 2
---

<!-- _pages/preprint.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

{% bibliography --query @*[@preprint=true] %}

</div>
