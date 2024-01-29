---
layout: single
title: "Sciences économiques et sociales"
permalink: /ses/
author_profile: true
---

{% include base_path %}

A propos
======
* Cette page rassemble mon travail de visualisation sur l'évolution de l'enseignement des sciences économiques et sociales

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
