---
layout: default
title: Annotations
permalink: /annotations/
---

List of entries by annotations:
{% for annot in site.annotations %}
  <a href="{{annot.url}}">{{annot.name}}</a>
{% endfor %}
