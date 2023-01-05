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
    <td><img src="{{ page.path | remove: page.name }}/{{ page.img }}" width="128" height="128"></td>
    <td><a href="/EmbracingDigitalTransformation/{{ page.url }}">{{ page.number}} - {{ page.title }}</a>
    <td>{{ page.summary }}</td>
</tr>

{% endif %}
{% endfor %}

</table>
