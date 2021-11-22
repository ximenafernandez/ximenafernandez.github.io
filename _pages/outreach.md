---
layout: archive
title: "Outreach"
permalink: /outreach/
author_profile: true
---

## Talks

{% include base_path %}

{% for post in site.talks-outreach reversed %}
  {% include archive-single.html %}
{% endfor %}


## Tutorials

<ul>
<li> [Discrete Morse Theory 2.0](https://www.youtube.com/watch?v=mZ2FIyg7NJ4)
</li>
<li> [Intrinsic Persistent Homology](https://www.youtube.com/watch?v=1lP9ndiM60o)
</li>
</ul>

## Publications

{% include base_path %}

{% for post in site.publications-outreach reversed %}
  {% include archive-single.html %}
{% endfor %}
