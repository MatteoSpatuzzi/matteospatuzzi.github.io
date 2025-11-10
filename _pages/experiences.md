---
title: Portfolio
layout: collection
permalink: /experiences/
collection: experiences
entries_layout: grid
classes: wide
---

{% include base_path %}

{% for post in site.experiences reversed %}
  {% include archive-single.html %}
{% endfor %}
