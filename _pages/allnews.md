---
title: "All news"
layout: textlay
excerpt: "All news"
sitemap: false
permalink: /allnews
---

# All news

<div markdown="0">
{% for item in site.data.news %}
<p>{{ item.date }} &nbsp; {{ item.headline }}</p>
{% endfor %}
</div>