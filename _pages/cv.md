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
* M.S. in Biomedical Systems Informatics, Yonsei University, Feb 2027 (expected)
  * Thesis: *Development and Application of a Standardized Common Data Model for Medical Device Post-Market Surveillance*
  * Advisor: Prof. Seng Chan You
<!-- TODO: add your B.S. degree, e.g. * B.S. in ..., University, Year -->

<!-- TODO: add Skills (e.g. R, SQL, Python, OMOP CDM, ATLAS, HADES) and uncomment
Skills
======
* Skill 1
-->

Honors & Awards
======
* Best Poster Award, 2026 KOSMI Spring Conference, Jun 2026
* Grand Prize, Medical Device CDM Analysis Ideathon, hosted by NIDS, May 2026
* Best Poster Award, SIDDS 2026, Apr 2026

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Presentations
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Lectures
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
