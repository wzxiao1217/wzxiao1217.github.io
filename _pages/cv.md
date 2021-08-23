---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Education
* Candidate for B.Eng. in Biomedical Engineering, Shanghai Jiao Tong University, 2022(expected)

## Research Experience
* Shanghai Artificial Intelligence Laboratory, July 2021 - present
  * Research intern, remotely supervised by Prof. Qi Dou
  * Develop algorithms for detection and segmentation of cerebral microbleeds in MRI.

* Institute of Medical Robotics, SJTU, Nov. 2020 - June 2021
  * Undergraduate Research Assistant, supervised by Prof. Guoyan Zheng
  * Reproduced several methods for 3D reconstruction of knee bones from multi-planar X-ray images, including U-Net like reconstruction network and patient-specific deep network.
  * Built a statistical deformable model of femur and incorporated the shape prior information into deep learning based registration framework. The proposed method achieved 0.94 average Dice score, while it had less parameters and much smoother deformation field.
  * Established a deep learning based unsupervised joint affine and deformable registration framework for femur and pelvis registration, achieving 0.96 and 0.92 Dice performance.

* Med-X Research Institute, SJTU, July 2019 - Oct. 2020
  * Undergraduate Research Assistant, supervised by Prof. Xiaohua Qian
  * Implemented and improved a kernel penalized SVM based feature selection model to predict transition from mild cognitive impairment to Alzheimer’s disease in 3 years, achieving 0.82 balanced accuracy.
  * Developed feature selection models based on prior knowledge for identifying DNA methylation biomarkers in Alzheimer's disease.
  * Designed a uniform spiral transformation method for pancreatic cancer segmentation, applying 3D contextual information in a 2D network. The proposed segmentation framework achieved a state-of-the-art 0.65 Dice performance.

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
  
Service and leadership
======
* Currently signed in to 43 different slack teams
