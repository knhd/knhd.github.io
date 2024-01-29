---
layout: single
title: "Parcoursup"
permalink: /parcoursup/
author_profile: true
---

{% include base_path %}

A propos
======
* Cette page rassemble mon travail de visualisation sur les données parcoursup

Par exemple
<iframe width="900" height="800" frameborder="0" scrolling="no" src="parcoursup_2023.html"> </iframe>

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
