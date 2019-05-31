---
#layout: archive
title: "Talks"
permalink: /talks/
author_profile: true
google_site_verification : qLmB3ZHKKYmvqD7qykfvK5XK4WaMZYXM-dFR-ZyAkmo
---
Invited Talks
------
* __Machine Learning for Home-based Healthcare Monitoring__<br/>*Department of Electronics and Computer Science, University of Southampton*<br/>28 May 2019

* __Temporal Structure Modelling for Audio Event Detection__<br/>*School of Computing, University of Kent (Medway)*<br/>31 January 2018

* __Some Perspectives on Audio Event Detection__<br/>*Pattern Recognition in Embedded Systems Group, Technical University Dortmund*<br/>02 December 2016

* __Audio Event Detection, Classification, and Beyond__<br/>*Institute for Natural Language Processing, University of Stuttgart*<br/>23 May 2016

* __Acoustic Event Detection with Random Regression Forests__<br/>*Department of Medical Physics and Acoustics, Carl von Ossietzky University of Oldenburg*<br/>02 June 2015


{% for post in site.talks reversed %}
  {% include archive-single-talk.html %}
{% endfor %}
