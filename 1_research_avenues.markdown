---
layout: page
title: Research
permalink: /research/
---

Broadly speaking my work is on Physics &cap; Machine Learning.

These pages shall provide a bit more information on what we are working on (current research) and where this work has emerged from (past research).

{% for themes in site.research_avenues %}

<a href="{{ themes.url | prepend: site.baseurl }}">
    {{ themes.title }}
</a>

<p class="post-excerpt">{{ themes.description | truncate: 160 }}</p>

{% endfor %}

If you want to hear more about research in this direction, tune in to [physicsmeetsml.org](www.physicsmeetsml.org) which I am co-organising.
