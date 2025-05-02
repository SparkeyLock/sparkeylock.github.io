---
layout: archive
title: "Blog posts"
permalink: /year-archive/
author_profile: false
redirect_from:
  - /wordpress/blog-posts/
---

{% include base_path %}

{% assign sorted_posts = site.posts | sort: 'date' | reverse %}
{% for post in sorted_posts %}
  {% include archive-single.html %}
{% endfor %}
