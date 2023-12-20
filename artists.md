---
layout: page
title: "artists"
permalink: /artists/
---

We work with a range of emerging and establihsed artists based in South Korea and international artists whose practice resonates with us. We do not commercially represent artists. Instead, we collaborate with artists, curators, collectors to create meaningful new art works and exhibitions, and placing the works in private and public collections.




<aside>
  {% for post in site.categories.artists %}
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
 


 