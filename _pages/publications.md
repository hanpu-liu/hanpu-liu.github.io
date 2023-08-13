---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Hanpu Liu's full publication list can be found on <a href="https://ui.adsabs.harvard.edu/search/q=orcid%3A0000-0003-2488-4667&sort=date+desc" target="_blank" rel="noopener noreferrer">ADS</a><i class="fa fa-fw fa-external-link" aria-hidden="true"></i> or <a href="https://arxiv.org/search/advanced?advanced=&terms-0-term=Hanpu+Liu&terms-0-field=author" target="_blank" rel="noopener noreferrer">arXiv</a><i class="fa fa-fw fa-external-link" aria-hidden="true"></i>.

{% comment %}

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
{% endcomment %}
