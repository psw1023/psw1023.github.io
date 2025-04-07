---
title: "Paper Review"
layout: category
permalink: /categories/paper-review/ # url
author_profile: true
types: posts
sidebar:
    nav: "sidebar-category"
---

{% assign posts = site.categories['paper-review']%}
{% for post in posts %}
  {% include archive-single.html type=page.entries_layout %}
{% endfor %}