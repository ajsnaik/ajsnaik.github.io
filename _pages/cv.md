---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D in Computer Science and Engineering, IIT Bombay, (2024 - ) (ongoing)
* M.Sc in Cognitive Science, IIT Bombay, (2020-22)
* B.Tech in Electronics and Telecommunications, Govt. College of Engineering Amravati, (2012-16)

Work experience
======
* July 2022 - July 2024: ICICI Bank 
  * part of the Data Science and Analytics Team (DSAG)
  * worked on anti-fraud and compliance analytics 

* January 2017 - January 2018: Cognizant Technology Solutions
  * part of testing team working on an online loan portal for a US bank.
 
<!-- * Summer 2015: Research Assistant
  * Github University
  * Duties included: Tagging issues
  * Supervisor: Professor Git -->
  

Publications
======
  {% assign post = site.publications | where: "relative_path", "_publications/2024-02-17-paper-title-number-4.md" | first %}
  <ul>
    {% include archive-single-cv.html %}
  </ul>
  
{% comment %}
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams
{% endcomment %}
