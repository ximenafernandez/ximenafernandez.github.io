---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

My research interests falls into two main areas: 
* Applied Algebraic Topology and Geometry,
* Computational and Combinatorial Topology.

I am specially interested in Topological Data Analysis and Manifold Learning methods.


## Publications

<nbsp>

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}