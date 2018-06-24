---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

  You can find my Google Scholar profile <u><a href="https://scholar.google.com/citations?hl=en&user=RegoACcAAAAJ">here</a></u>.

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
