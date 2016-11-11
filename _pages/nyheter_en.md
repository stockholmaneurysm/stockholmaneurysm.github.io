---
title: "News"
layout: archive
excerpt: "News"
permalink: en/news.html
lang: en
alt_url: "/sv/news.html"
alt_lang: "Svenska"

---

<!--
{% for collection in site.collections.news.docs %}
  <h3>{{ collection.title }}</h3>
{% endfor %}
-->

<ul>
{% for topic in site.news %}
    <h3><li><a href="{{ site.baseurl }}{{ topic.url }}">{{topic.title}}</a></li></h3>

    {{ topic.preview }}
{% endfor %}
</ul>
