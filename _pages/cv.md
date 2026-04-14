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
* PH.D Candidate in Computer Science and Technology, Peking University, 2022-Now
* B.S. in Computer Science and Technology, Peking University, 2017-2022

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
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
* Reviewer, IEEE Transactions on Information Forensics and Security (TIFS), 2025
