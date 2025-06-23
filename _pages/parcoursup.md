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
<iframe width="900" height="800" frameborder="0" scrolling="no" src="parcoursup_2023_all"> </iframe>

<div class="flourish-embed flourish-hierarchy" data-src="visualisation/23884241"><script src="https://public.flourish.studio/resources/embed.js"></script><noscript><img src="https://public.flourish.studio/visualisation/23884241/thumbnail" width="100%" alt="hierarchy visualization" /></noscript></div>

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
