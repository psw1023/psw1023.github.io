---
title: "Theory"
layout: category
permalink: /categories/theory/ # url
author_profile: true
types: posts
sidebar:
    nav: "sidebar-category"
---

{% assign posts = site.categories['theory']%}
{% for post in posts %}
  {% include archive-single.html type=page.entries_layout %}
{% endfor %}