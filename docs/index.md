---
layout: default
title: Overview
nav_order: 1
---
# Embracing Digital Transformation

This is the description.

<h1>Episodes</h1>
<table>
{% for page in site.pages %}
{% if page.number %}
<tr>
<td><img src="{{ page.path | remove: page.name }}/{{ page.img }}" width="100" height="100"></td>
<td>{{ page.number }}</td>
<td><a href="/EmbracingDigitalTransformation/{{ page.url }}">{{ page.title }}</a>
<td>{{ page.summary }}</td>
</tr>
{% endif %}
{% endfor %}
</table>
