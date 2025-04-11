---
title: "Theory"
layout: category
permalink: /categories/theory/ # url
author_profile: true
sidebar_main: true
---

{% assign posts = site.categories['Theory'] %}
{% for post in posts %} {% include archive-single2.html type=page.entries_layout %} {% endfor %}