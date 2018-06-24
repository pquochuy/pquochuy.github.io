---
layout: archive
title: "Invited Talks"
permalink: /talks/
author_profile: true
---

#<p style="text-decoration:underline;"><a href="/talkmap.html">See a map of all the places I've given a talk!</a></p>

**Huy Phan**.  ___Temporal Structure Modelling for Audio Event Detection___. *School of Computing, University of Kent (Medway)*, January 2018

{% for post in site.talks reversed %}
  {% include archive-single-talk.html %}
{% endfor %}
