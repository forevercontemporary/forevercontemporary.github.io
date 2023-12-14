---
layout: page
title: "learning"
permalink: /learning/
---

workshops,education,
forever space for contemporary art
<p>Posts in category "learning" are:</p>

<ul>
  {% for post in site.categories.learning %}
    {% if post.url %}
        <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul> 