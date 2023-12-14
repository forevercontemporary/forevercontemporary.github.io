---
layout: collection
title: "작품 소장하기"
permalink: /collecting/
---

작품을 소개하고 

Permanent collections of forever.
forever space for contemporary art
 <ul>
  {% for post in site.categories.collection %}
    {% if post.url %}
        <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul> 