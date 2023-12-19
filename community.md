---
layout: residency
title: "공동체/ 생태계 "
permalink: /community/
---


# Learning
 
 Educational programs

# Journal

 
 <ul>
  {% for post in site.categories.journal %}
    {% if post.url %}
        <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul> 

# 레지던시
