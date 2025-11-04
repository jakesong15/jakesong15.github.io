---
layout: single
title: "Research"
permalink: /research/
author_profile: true
---
<h2 style='margin-top: 20px; border-bottom: 1px solid mix(#fff, $gray, 90%); padding-bottom: 5px;'>Current Interests</h2> 

I am interested in the unique mechanical properties of biological soft materials, such as biopolymer hydrogels, extracellular matrices, and tissues. Unlike synthetic polymer materials in which significant physical insights have been gained over the last few decades, we have yet to develop comparable physical insights in biopolymers and tissues due to their non-Gaussian structural conformations, multi-component microstructures and interactions, and non-trivial mechanical responses. Yet, the mechanics of biological materials are known to play a decisive role in biology, governing the fate of cells residing in such mechanical environments through mechanotransduction. As such, a deep understanding of the multi-scale mechanical properties of these biological materials holds the key to understanding how the development and disease of tissues are regulated by mechanical cues within the tissues, and developing materials solutions for in vitro models and engineered tissues.

<h2 style='margin-top: 30px; border-bottom: 1px solid mix(#fff, $gray, 90%); padding-bottom: 5px;'>Previous Projects</h2> 

I have been involved in a wide range of research projects in polymers, soft matter, and living systems throughout my time at Stanford, MIT, and Northwestern. You can find examples of these projects below:

<nbsp>

{% include base_path %}

{% assign ordered_pages = site.research %}

{% for post in ordered_pages %} {% include archive-single.html type="grid" %} {% endfor %}
