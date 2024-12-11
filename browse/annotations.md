---
layout: default
title: Annotations
---

List of annotations:
{% for annot in site.annotations %}
  <a class="btn btn-sm btn-pill btn-annotation" href="{{ annot.url | relative_url }}">{{annot.title}}</a>
{% endfor %}

