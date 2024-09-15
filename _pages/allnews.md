---
title: "News"
layout: textlay
excerpt: "BioAI Research Group at the University of Glasgow"
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}
<p>{{ article.date }} <br> {{ article.headline | markdownify}}</p>
{% endfor %}
