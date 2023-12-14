---
layout: collection
title: " 소장품 소개 "
permalink: /collection/
---


Permanent collections of forever.
forever space for contemporary art
 <ul>
  {% for post in site.categories.collection %}
    {% if post.url %}
        <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul> 