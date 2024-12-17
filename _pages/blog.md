---
layout: archive
title: "Blog Posts"
permalink: /blog/
author_profile: true
---

Welcome to my blog! Here I share my latest research progress, insights, and thoughts on quantum physics and technology.

{% for post in site.posts %}
  {% include archive-single.html %}
{% endfor %}
