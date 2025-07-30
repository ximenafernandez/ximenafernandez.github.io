---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

My PhD thesis is about:

* ['Combinatorial methods and algorithms in low-dimensional topology and the Andrews-Curtis conjecture'.](http://cms.dm.uba.ar/academico/carreras/doctorado/Tesis_Ximena_Fernandez.pdf)  University of Buenos Aires (2017). 

My current research interests fall into the following areas: 
* Topological Data Analysis,
* Computational Geometry,
* Combinatorial Homotopy Theory.

I have organized the [Tube Neighborhood Meeting](https://sites.google.com/view/tubeneighbourhood/) at City University of London on 17th July 2025.

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
