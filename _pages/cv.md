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
* Ph.D in Computer Engineering, University of Padova, Italy, 2024-2027 (expected);
* M.S. in Computer Engineering, University of Padova, Italy, 110/110 cum laude, 2021-2024;
* B.S. in Information Engineering, University of Padova, Italy, 109/110, 2018-2021;
* High School Scientific Diploma, Liceo Scientifico J. Da Ponte, Bassano del Grappa (VI), Italy, 96/100, 2013-2018.

Work Experiences
======
* November 2024 - Current: Researcher at Fondazione Bruno Kessler.
  * Group: Data Science for Health (DSH);
  * Topics: Deep Learning methods for complex biomedical tasks involving multimodal data.

Teaching
======
* Fall 2025: Teaching Assistant.
  * University of Padova;
  * Lectures on Machine Learning, laboratory sessions of Python programming.
  
Skills
======
* **Algorithms**: design, implementation, testing and debugging of rigorous and efficient algorithms;
* **Python Programming**: PyTorch, Scikit-Learn, Pandas, Numpy, Matplotlib, Seaborn;
* **Version Control**: Git, GitHub, Bitbucket;
* **Operating Systems**: Linux, MacOS, Windows;
* **Soft Skills**: planning, adaptability, precision, empathy, commitment, problem solving, team working.

Languages
======
* **Italian**: native;
* **English**: B2;
* **Spanish**: bilingual.

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

Software
======
* **CPhyT-GNN**: method based on a Graph Neural Network to compute unsupervised embeddings from tumor phylogenetic trees.
The embeddings are general-purpose and examples of applications such as survival time prediction and phylogenetic trees clustering for cancer clonal evolution modeling are provided. 
You can find the repository [at this link](https://github.com/VandinLab/CPhyT-GNN).