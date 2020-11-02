---
title: "Sites"
layout: textlay
excerpt: " "
sitemap: false
permalink: /sites.html
---

# News

{% for article in site.data.news %}
<p>{{ article.date }} <br>
<em>{{ article.headline }}</em></p>
{% endfor %}
