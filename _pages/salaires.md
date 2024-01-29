---
layout: single
title: "Salaires enseignants"
permalink: /salaires/
author_profile: true
---

{% include base_path %}

A propos
======
* Cette page rassemble mon travail de visualisation sur l'évolution des salaires enseignants sur longue période

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
