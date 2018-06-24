---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{ if author.googlescholar }
  You can find my Google Scholar profile <u><a href="{{author.googlescholar}}">here</a>.</u>
{ endif }

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
