---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Hanpu Liu's full publication list can be found on <a href="https://ui.adsabs.harvard.edu/search/q=orcid%3A0000-0003-2488-4667&sort=date+desc" target="_blank" rel="noopener noreferrer">NASA ADS</a>, <a href="https://scholar.google.com/citations?hl=en&user=eJziUPUAAAAJ">Google Scholar</a> or <a href="https://arxiv.org/search/advanced?advanced=&terms-0-term=Hanpu+Liu&terms-0-field=author" target="_blank" rel="noopener noreferrer">arXiv</a>.

## First-author papers

<b>Liu, H.</b>, Inayoshi, K. 2025, PRD, 111, 043012: <a href="https://ui.adsabs.harvard.edu/abs/2025PhRvD.111d3012L/abstract" target="_blank" rel="noopener noreferrer">Gravitational wave forecasts constrained by JWST AGN observations for early massive black hole mergers</a>

<b>Liu, H.</b>, Bai, X.-N. 2023, MNRAS, 526, 80: <a href="https://ui.adsabs.harvard.edu/abs/2023MNRAS.526...80L/abstract" target="_blank" rel="noopener noreferrer">The dusty Rossby wave instability (DRWI): linear analysis and simulations of turbulent dust-trapping rings in protoplanetary discs</a>

<b>Liu, H.</b>, Herczeg, G.J., Johnstone, D., et al. 2022, ApJ, 936, 152: <a href="https://ui.adsabs.harvard.edu/abs/2022ApJ...936..152L/abstract" target="_blank" rel="noopener noreferrer">Diagnosing FU Ori-like Sources: The Parameter Space of Viscously Heated Disks in the Optical and Near-infrared</a>

{% comment %}

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
{% endcomment %}
