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


<ul>
{% for topic in site.nyheter %}
  {{ topic.date}}<p>
  <b><a href="{{ site.baseurl }}{{ topic.url }}">{{topic.title}}</a></b><p>
  {{ topic.preview }}
    <hr>
{% endfor %}
