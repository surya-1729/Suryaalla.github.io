---
title: "Non-Rigid Shape Correspondence"
excerpt: "<img width='50%' src='/images/previews/laehner2016elastic2D3D.png'>"
collection: portfolio
---

DFG Sachbeihilfeproject 'Robust Spectral Non-Rigid Shape Correspondence' (3 years)

## Publications

{% for post in site.publications reversed %}
  {% if post.categories contains 'correspondence' %}
    {% include archive-single-publication.html %}
  {% endif %}
{% endfor %}
