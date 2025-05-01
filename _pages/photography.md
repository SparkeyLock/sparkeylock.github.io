---
layout: archive
title: "Photography"
permalink: /photography/
author_profile: true
excerpt: "My photography collection"
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
---

{% include base_path %}

{% assign sorted_photography = site.photography | sort: 'date' | reverse %}
{% for post in sorted_photography %}
  {% include archive-single.html show_excerpt=false %}
{% endfor %}
