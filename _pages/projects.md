---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: false
---

{% include base_path %}

{% assign sorted_posts = site.projects | sort: 'date' | reverse %}
{% for post in sorted_posts %}
  {% include archive-single.html %}
{% endfor %}
