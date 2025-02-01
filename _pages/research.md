---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

## Current Interests

I am interested in the unique mechanical properties of biological materials, such as biopolymer hydrogels, extracellular matrices, and tissues. Unlike synthetic polymer materials in which significant physical insights have been gained over the last few decades, we have yet to develop comparable physical insights in biopolymers and tissues due to their non-Gaussian structural conformations, multi-component microstructures and interactions, and non-trivial mechanical responses. Yet, the mechanics of biological materials are known to play a decisive role in biology, governing the fate of cells residing in such mechanical environments through mechanosensitive signaling processes. As such, a deep understanding of the mechanics of biological materials holds the key to understanding how materials properties regulate the development and disease of tissues, and developing engineered polymeric materials to model these behaviors for biomedical applications.   

## Previous Projects


{% include base_path %}


<!-- New style rendering if publication categories are defined -->
{% if site.research_category %}
  {% for category in site.research_category  %}
    {% assign title_shown = false %}
    {% for post in site.research reversed %}
      {% if post.category != category[0] %}
        {% continue %}
      {% endif %}
      {% unless title_shown %}
        <h2>{{ category[1].title }}</h2><hr />
        {% assign title_shown = true %}
      {% endunless %}
      {% include archive-single.html %}
    {% endfor %}
  {% endfor %}
{% else %}
  {% for post in site.research reversed %}
    {% include archive-single.html %}
  {% endfor %}
{% endif %}
