---
layout: default
title: Overview
nav_order: 1
---
# Embracing Digital Transformation

This is the description.

<h1>Episodes</h1>
<ul>

{% for page in site.pages %}
{% if page.number %}

<li>
    <img src="{{ page.path | remove: page.name }}/{{ page.img }}" style="float:left;" width="128" height="128">
    <div style="clear:both;">
        <a href="/EmbracingDigitalTransformation/{{ page.url }}">{{ page.number}} - {{ page.title }}</a><br>
        {{ page.summary }}
    </div>
</li>
{% endif %}
{% endfor %}

</ul>
