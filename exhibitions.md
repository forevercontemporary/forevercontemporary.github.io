---
layout: page
title: "exhibitions"
permalink: /exhibitions/
---


2024 


Dark Night of the Universe, Muljilsegye Choi Soojin Solo Exhibition 



2023 

Friend's Neighborhood, Curated by Taeyoon Choi
 



2024 

영혼의 어두운 밤, 물질세계 
최수진 개인전

<p>전시 아카이브:</p>

<ul>
  {% for post in site.categories.exhibition %}
    {% if post.url %}
        <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul> 