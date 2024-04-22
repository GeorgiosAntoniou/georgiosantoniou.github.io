---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

[Working Papers](#working) &nbsp; &nbsp; &nbsp; &nbsp; [Conference Proceedings](#conf) &nbsp; &nbsp; &nbsp; &nbsp; [Journal Publications](#journal)


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
