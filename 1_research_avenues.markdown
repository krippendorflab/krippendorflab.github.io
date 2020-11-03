---
layout: default
title: Research
---

Broadly speaking my work is on Physics &#2229; Machine Learning.

These pages shall provide a bit more information on what we are working on (current research) and where this work has emerged from (past research).

{% for themes in site.research_avenues %}

<a href="{{ themes.url | prepend: site.baseurl }}">
    {{ themes.title }}
</a>

<p class="post-excerpt">{{ themes.description | truncate: 160 }}</p>

{% endfor %}  
