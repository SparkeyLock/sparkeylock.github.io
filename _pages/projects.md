---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: false
---

{% include base_path %}

{% for post in site.projects %}
  <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
  <p>{{ post.excerpt }}</p>
{% endfor %}
