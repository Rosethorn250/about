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
* M.A. in Digital Humanities, University of Alberta, 2027 (expected)
* B.A. in English, University of Alberta, 2025

Work experience
======
* Fall 2025 - Current: Research Assistant
  * University of Alberta
  * Duties include: Public Outreach, Workshop Admin, Interview Recording and Questioning
  * Supervisor: Dr. PB Berge

* Fall 2023: Research Assistant
  * University of Alberta
  * Duties included: Interview Transcription Refinement
  * Supervisor: Dr. Sean Gouglas

<!--Publications-->
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
<!--Teaching-->
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

