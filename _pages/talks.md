---
layout: archive
title: ""
permalink: /talks/
author_profile: true
---

Invited Talks
------

___Temporal Structure Modelling for Audio Event Detection___<br/>*School of Computing, University of Kent (Medway)*<br/>31 January 2018

___Some Perspectives on Audio Event Detection___<br/>*Pattern Recognition in Embedded Systems Group, Technical University Dortmund*<br/>02 December 2016

___Audio Event Detection, Classification, and Beyond___<br/>*Institute for Natural Language Processing, University of Stuttgart*<br/>23 May 2016

___Acoustic Event Detection with Random Regression Forests___<br/>*Department of Medical Physics and Acoustics, Carl von Ossietzky University of Oldenburg*<br/>02 June 2015


{% for post in site.talks reversed %}
  {% include archive-single-talk.html %}
{% endfor %}
