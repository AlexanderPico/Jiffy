---
layout: annotation-page
name: First type
description: This is the first type of annotation for the entries in this site
---

List of entries with this annotation:
{% for entry in site.entries %}
  {% if entry.annotations contains "Type 1" %}
    <a href="{{entry.url}}">{{entry.title}}</a>
  {% endif %}
{% endfor %}
