---
layout: page
title: "artists"
permalink: /artists/
---

forever space for contemporary art is a community of artists, curators, organizers and writers.


<ul>

  {% for post in site.categories.artists %}
    {% if post.url %}
        <li><a href="{{ post.url }}">{{ post.title }} </a></li>
    {% endif %}
  {% endfor %}
</ul> 

 


 