---
layout: page
title: ""
permalink: /journal/
---


 
<aside>
  {% for post in site.categories.journal %}
    {% cycle 'add row' : '<div class="row">', '', '' %}
        <div class="column column-4">
            <div class="preview-panel">
                <a href="{{ post.url | prepend: site.baseurl }}">
                    <img src="{{ post.preview }}">
                </a>
                <div class="post-title">{{ post.title }}</div>
        <div class="post-summary">{{ post.summary }}</div>
           </div>
        </div>
{% cycle 'end row' : '', '', '</div>' %}
{% endfor %}
{% cycle 'end row' : '', '</div>', '</div>' %}

</aside>