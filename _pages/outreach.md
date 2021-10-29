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


## Publications

{% include base_path %}

{% for post in site.publications-outreach reversed %}
  {% include archive-single.html %}
{% endfor %}
