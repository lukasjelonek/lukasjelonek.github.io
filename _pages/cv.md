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
* B.S. in Bioinformatics & genome research, Bielefeld University, 2007
* M.S. in Bioinformatics & genome research, Bielefeld University, 2010

Work experience
======
* 2014-now: Scientific assistant
  * Justus-Liebig-University Gießen
  * Duties included: 
    * Teaching 
    * Data analysis
    * Workflow development
    * Development of distributed applications
  * Supervisor: Prof. Dr. Alexander Goesmann

* 2013: Scientific assistant
  * Bielefeld University
  * Duties included: Parallelization of bioinformatic tools
  * Supervisor: Dr. Alexander Goesmann

* 2010-2013: Phd student
  * Bielefeld University
  * Duties included: Fungal genome annotation, Software implementation (Java)
  * Supervisor: Dr. Alexander Goesmann

Skills
======
* Programming
  * Java
  * Groovy
  * Python
  * Javascript
* Distributed Applications
  * Vert.x
  * Cloud
* Classical web applications
  * Grails
* Bioinformatics
  * Genome annotation
* Teaching

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
