---
layout: archive
title: "Invited Talks"
permalink: /talks/
author_profile: true
---

___Temporal Structure Modelling for Audio Event Detection___. *School of Computing, University of Kent (Medway)*, 31 January 2018

___Some Perspectives on Audio Event Detection___. *Pattern Recognition in Embedded Systems Group, Technical University Dortmund*, 02 December 2016

___Audio Event Detection, Classification, and Beyond___. *Institute for Natural Language Processing, University of Stuttgart*, 23 May 2016

___Acoustic Event Detection with Random Regression Forests___. *Department of Medical Physics and Acoustics, Carl von Ossietzky University of Oldenburg*, 02 June 2015


{% for post in site.talks reversed %}
  {% include archive-single-talk.html %}
{% endfor %}
