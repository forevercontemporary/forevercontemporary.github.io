---
layout: residency
title: "residency"
permalink: /residency/
---

forever space for contemporary art
<p>Posts in category "residency" are:</p>

<ul>
  {% for post in site.categories.residency %}
    {% if post.url %}
        <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul> 