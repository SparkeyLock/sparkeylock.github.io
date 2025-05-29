---
layout: archive
title: "Portfolio"
permalink: /portfolio/
author_profile: false
---

{% include base_path %}

{% assign sorted_portfolio = site.portfolio | sort: 'date' | reverse %}
{% for post in sorted_portfolio %}
  {% include archive-single.html %}
{% endfor %}
