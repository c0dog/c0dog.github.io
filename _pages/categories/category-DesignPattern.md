---
title: "DesignPattern"
layout: archive
permalink: categories/DesignPattern
author_profile: true
sidebar_main: true
sidebar:
    nav: "docs"
classes: wide
---

{% assign posts = site.categories.DesignPattern %}
{% for post in posts %} {% include archive-single2.html type=page.entries_layout %} {% endfor %}