---
layout: default
title: Collection of Pages
---

{% for t in site.tutorials %}

<h2><a href="{{ t.url | site.baseurl | site.url}}">{{ t.title }}</a></h2>

<p class="post-excerpt">{{ t.description | truncate: 160 }}</p>

{% endfor %}  