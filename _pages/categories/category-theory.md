---
title: "Theory"
layout: category
permalink: /categories/theory/ # url
author_profile: true
types: categories
sidebar:
    nav: "sidebar-category"
---

{% assign posts = site.categories['Theory']%}
{% for post in posts %}
  {% include archive-single.html type=page.entries_layout %}
{% endfor %}