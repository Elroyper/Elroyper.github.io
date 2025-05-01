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
* M.S. in Big Data Technology, Peking University, 2026(expected)
* B.S. in Mathematics, Shandong University, 2024  


Work experience
======

  
Skills
======
* Machine Learning Technologies
  * Supervised Learning
  * Unsupervised Learning
  * Reinforcement Learning
  * Model Optimization and Tuning
* Large Language Model Deployment and Fine-tuning
  * Model Serving (e.g., TensorFlow Serving, TorchServe)
  * LLM Compression and Quantization
  * Prompt Engineering
  * Adapter Tuning / LoRA / Full Fine-tuning
* Model Security Techniques
  * Adversarial Attack and Defense
  * Model Robustness Evaluation


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
  

  
