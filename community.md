---
layout: residency
title: "공동체/ 생태계 "
permalink: /community/
---


# 배우기

# 소장품 

# 저널 


 
 <ul>
  {% for post in site.categories.journal %}
    {% if post.url %}
        <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul> 

# 레지던시