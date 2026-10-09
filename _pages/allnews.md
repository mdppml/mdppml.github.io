---
title: "News"
layout: textlay
excerpt: "News from the MDPPML group at the University of Tübingen."
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}

***{{ article.date }}***: **{{ article.headline }}**

> {{ article.detail }}

{% endfor %}
