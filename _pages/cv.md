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
* Ph.D. in Electrical Engineering, New York University, 2023 (expected)
* B.Tech. in Electrical Engineering, IIT Kanpur, 2018


Work experience
======
* Summer 2017: Research Assistant
  * New York University
  * Duties included: Developed a framework for quantifying the interdependencies between infrastructures using Dynamic Mode Decomposition (DMD). Constructed a multi layer network for visualization of the networks using the matrix from DMD. Analyzed the vulnerabilities in the network through motifs and markov decision rule model.
  * Supervisor: Professor Quanyan Zhu

* Summer 2016: Research Assistant
  * IIT Kanpur
  * Duties included: Studied various spectrum sensing schemes like GLRT, L-GLRT, Correlator, Energy Detector. Implemented the algorithms by simulating them in MATLAB using a large set of channel realizations. Analyzed the performance of each spectrum sensing scheme for various number of receivers and threshold values.
  * Supervisor: Professor Aditya Jagannatham
  
Skills
======
* Languages: Python, C/C++, MATLAB, Java, R, Verilog, VHDL
* Platforms: Linux (Ubuntu, Redhat Linux, Fedora, CentOS), Windows, Arduino, Raspberry, FPGA


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
  

