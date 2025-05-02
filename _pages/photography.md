---
layout: archive
title: "Photography"
permalink: /photography/
author_profile: true
---

{% include base_path %}

{% assign sorted_photography = site.photography | sort: 'date' | reverse %}
{% for post in sorted_photography %}
  {% include archive-single.html %}
{% endfor %}
