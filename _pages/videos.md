---
layout: archive
title: "Videos for fun"
permalink: /videos/
author_profile: true
---

This is a collection of videos.


{% include base_path %}

{% for post in site.videos reversed %}
  {% include archive-single.html %}
{% endfor %}
