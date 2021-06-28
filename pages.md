---
layout: default
title: Collection of Pages
---

{% for t in site.tutorials %}

<a href="{{ themes.url | prepend: site.baseurl }}">
  <h2>{{ t.title }}</h2>
</a>

<p class="post-excerpt">{{ t.description | truncate: 160 }}</p>

{% endfor %}  