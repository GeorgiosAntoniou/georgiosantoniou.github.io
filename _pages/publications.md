---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

[Papers](#papers) &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; [Theses](#theses)


You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>


{% include base_path %}

<!-- ## <span style="color: #3b5998">Working Papers </span> -->
<h2 id="papers">
Papers
</h2>
{% for post in site.publications reversed %}
  {% include paper-single-working.html %}
{% endfor %}