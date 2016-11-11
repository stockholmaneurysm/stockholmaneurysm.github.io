---
title: "Nyheter"
layout: archive
excerpt: "Nyheter"
permalink: sv/news.html
lang: sv
alt_url: "/en/news.html"
alt_lang: "English"
---

<!--
{% for collection in site.collections.news.docs %}
  <h3>{{ collection.title }}</h3>
{% endfor %}
-->

Nyheter som rör STAR-gruppen:

<ul>
{% for topic in site.nyheter %}
    <h3><a href="{{ site.baseurl }}{{ topic.url }}">{{topic.title}}</a></h3>
    {{ topic.date}} <p>

    {{ topic.preview }}
{% endfor %}
</ul>
