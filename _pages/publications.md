---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Here you can find selected publications grouped by topic and pre-prints of things I'm currently working on.

Disease progression modelling: methods
===

[Learning transition times in event sequences: the temporal event-based model of disease progression](http://pawij.github.io/files/Wijeratne-Alexander2021_Chapter_LearningTransitionTimesInEvent.pdf)

Disease progression modelling: application
===

[An image-based model of brain volume biomarker changes in Huntington's disease](http://pawij.github.io/files/paper_acn_2018.pdf)

Clinical study analysis
===

[Robust markers and sample sizes for multicenter trials of Huntington disease](http://pawij.github.io/files/paper_an_2020.pdf)

Drug delivery modelling
===

[A quantitative in silico platform for simulating cytotoxic and nanoparticle drug delivery to solid tumours](http://pawij.github.io/files/paper_rsif_2019.pdf)

Cancer growth modelling
===

[Multiscale biphasic modelling of peritumoural collagen microstructure: The effect of tumour growth on permeability and fluid flow](http://pawij.github.io/files/paper_pone_2017.pdf)

Inverse problems in particle physics
===

[Measurements of the pseudorapidity dependence of the total transverse energy in proton-proton collisions at √s=7 TeV with ATLAS](http://pawij.github.io/files/paper_jhep_2012.pdf)

<!-- {% include base_path %} -->

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
