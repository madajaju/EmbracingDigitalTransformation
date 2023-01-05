---
layout: default
title: Overview
nav_order: 1
---
# Embracing Digital Transformation

This is the description.

<h1>Episodes</h1>
<ul>

Tags:

{{ site.tags }}

:Tags

{% for page in site.pages %}
{% if page.number %}

<li>
    <img class="thumbnail" src="{{ page.path | remove: page.name }}/{{ page.img }}" width="128" height="128">
    <a href="/EmbracingDigitalTransformation/{{ page.url }}">{{ page.number}} - {{ page.title }}</a><br>
    {{ page.summary }}
</li>
{% endif %}
{% endfor %}
</ul>

<style>
.thumbnail {
    float: left;
    margin: 0 15px 0 0;
}
li {
    list-style-type:none;
    margin: 10px 0;
}
</style>

