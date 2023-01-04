---
layout: default
title: Overview
nav_order: 1
---
# Embracing Digital Transformation

This is the description.


<ul>
{% for post in site.posts %}
<li>
<a href="{{post.url}}">{{ post.title }} </a> - {{ post.excerpt }}
</li>
{% endfor %}
</ul>
