---
title: "Paper Review"
layout: category
permalink: /categories/paper-review/ # url
author_profile: true
types: categories
sidebar:
    nav: "sidebar-category"
---

{% assign posts = site.categories['Paper Review']%}
{% for post in posts %}
  {% include archive-single.html type=page.entries_layout %}
{% endfor %}