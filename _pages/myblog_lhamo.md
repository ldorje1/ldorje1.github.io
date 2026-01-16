---
title: "Blog"
permalink: /blog/
layout: archive
author_profile: true
---

{% include base_path %}

{% for post in site.posts %}
  {% include archive-single.html %}
{% endfor %}

