---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Here you can find selected publications grouped by topic and pre-prints of things I'm currently working on.

Progression modelling: Methods
===

[Unscrambling disease progression at scale: fast inference of event permutations with optimal transport](https://proceedings.neurips.cc/paper_files/paper/2024/hash/73c362193e3e23188b2a74de7824cc4c-Abstract-Conference.html)

[Subtype and stage inference with timescales](https://link.springer.com/chapter/10.1007/978-3-031-34048-2_2)

[The temporal event-based model: Learning event timelines in progressive diseases](https://direct.mit.edu/imag/article/doi/10.1162/imag_a_00010/117183/The-temporal-event-based-model-Learning-event)

Progression modelling: Applications
===

[Uncovering spatiotemporal patterns of atrophy in progressive supranuclear palsy using unsupervised machine learning](http://dx.doi.org/10.1093/braincomms/fcad048)

[Identifying multiple sclerosis subtypes using unsupervised machine learning and MRI data](https://www.nature.com/articles/s41467-021-22265-2)

[An image-based model of brain volume biomarker changes in Huntington's disease](http://pawij.github.io/files/paper_acn_2018.pdf)

Software development
===

[pySuStaIn: a Python implementation of the Subtype and Stage Inference algorithm](https://pubmed.ncbi.nlm.nih.gov/34926780/)

Clinical study analysis
===

[Characterizing developing executive functions in the first 1000 days in South Africa and Malawi: The Khula Study](https://wellcomeopenresearch.org/articles/9-157)

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
