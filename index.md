---
title: "Stockholm Aneurysm Research Group"
layout: splash
excerpt: "STAR"


feature_row:
  - image_path: vascular_surg.jpg
    alt: "Clinical medicine"
    title: "Clinical medicine"
    excerpt: "Clinical and patient-oriented research at the Karolinska University Hospital."
  - image_path: vasc_surg_edited.png
    alt: "Biomechanical simulations"
    title: "Biomechanical simulations"
    excerpt: "State-of-the-art biomechanical simulations."
  - image_path: cellular_edit.png
    title: "Cellular and molecular biology"
    excerpt: "Cellular and molecular biological investigations of aneurysms."

feature_row4:
  - url: /research-area.html
    btn_label: "Learn more"
    btn_class: "btn--inverse"

lang: en
alt_lang: "Sv"
alt_url: "/sv/splash.html"
---

Stockholm Aneurysm Research Group
=================================
{: .text-center}
<p>
{% include feature_row %}
<p>



<h3 class="archive__subtitle">Nyheter</h3>

<ul>
{% for topic in site.nyheter %}
    <h3><a href="{{ site.baseurl }}{{ topic.url }}">{{topic.title}}</a></h3>
    <b>{{ topic.date}} </b><p>

    {{ topic.preview }}
{% endfor %}
</ul>
