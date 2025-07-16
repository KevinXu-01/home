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
* M.S. in NERCMS, School of Computer Science, Wuhan University, 2022 - 2025
* B.S. in School of Computer Science, Wuhan University, 2018 - 2022

Work experience
======
* Spring 2024: TeleTrip
  * RAG
  * Pipeline latency optimization

* Now: Controllable Text-to-Video Generation
  * Data pipeline
  * Conditional Human-centric Video Generation
  
Skills
======
* Programming
* Badminton
* Cycling

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
    
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
