---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

My PhD thesis is about:

* ['Combinatorial methods and algorithms in low-dimensional topology and the Andrews-Curtis conjecture'.](http://cms.dm.uba.ar/academico/carreras/doctorado/Tesis_Ximena_Fernandez.pdf)  University of Buenos Aires (2017). 

My current research interests fall into two main areas: 
* Applied Algebraic Topology and Geometry,
* Computational and Combinatorial Topology.

I am specially interested in Topological Data Analysis, Geometric Inference and Homotopy Theory.

I am co-organizing the [London-Oxford TDA Seminar. ](https://sites.google.com/view/londoxtda/home )  

## Publications & preprints

<nbsp>

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
