---
layout: archive
title: "Homepage"
permalink: /cv/
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
Research Assistant | Moder Merging (10.2024-05.2025)
Supervisor: Prof. Hongxia Yang, Department of Computing, The Hong Kong Polytechnic University, Hong Kong
* Led the team to develop a resource-efficient framework for merging domain-specific LLMs to enhance reasoning abilities. The framework supports merging models of both similar and different architectures using layer-wise weight 
strategies and probabilistic knowledge from fine-tuning data. This work demonstrated that merging expert models 
improves reasoning capabilities, offering an efficient, decentralized alternative to traditional centralized LLMs.

Development Engineer | Data Closed-loop (08.2023-08.2024)
R & D Department, iMotion Automotive GmbH, Germany 
* Developed automated pre-processing pipelines for data processing, including image separation, pre-recognition, and 
storage. Built a YOLO-based anonymization model to remove personal information, such as license plates and faces, 
ensuring GDPR compliance. Optimized algorithm performance through multi-processing and asynchronous GPU and 
CPU resource management, and successfully deployed the model on the cloud. 

Data Scientisit Intern | Continuous Intraday Market Forecasting and Optimizing (05.2022-06.2023)
* Developed predictive models to forecast average electricity prices one hour before delivery in the continuous intraday market. Compared various approaches such as time-varying regression, LSTM, MLP, and proposed a Hierarchical 
Linear Model to address missing data. Integrated forecasts into rolling intrinsic algorithms, enabling the optimizer to 
leverage future price insights for smarter decision-making. 
  
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
