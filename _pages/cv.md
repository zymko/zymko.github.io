---
layout: archive
title: "Homepage"
permalink: /homepage/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D in The Hong Kong Polytechnic University, 2028 (expected)
* M.Sc. in Techische Universität München, 2023
* B.E. in Harbin Institute of Technology, 2019

Work experience
======
Research Assistant | Moder Merging (10.2023-05.2024)
Supervisor: Prof. Hongxia Yang, Department of Computing, The Hong Kong Polytechnic University, Hong Kong
  * Led the team to develop a resource-efficient framework for merging domain-specific LLMs to enhance reasoning abilities. The framework supports merging models of both similar and different architectures using layer-wise weight 
strategies and probabilistic knowledge from fine-tuning data. This work demonstrated that merging expert models 
improves reasoning capabilities, offering an efficient, decentralized alternative to traditional centralized LLMs.

* Fall 2015: Research Assistant
  * Github University
  * Duties included: Merging pull requests
  * Supervisor: Professor Hub

* Summer 2015: Research Assistant
  * Github University
  * Duties included: Tagging issues
  * Supervisor: Professor Git
  
Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
<!-- Talks
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
* Currently signed in to 43 different slack teams -->
