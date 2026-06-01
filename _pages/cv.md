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

* **Ph.D, Computer Vision and Deep Learning** — University of Surrey, 2023–2027 (expected)
* **M.Sc, Artificial Intelligence** — University of Surrey, 2023–2024
* **B.Eng, Electrical and Electronic Engineering** — Coventry University, 2019–2022

## Work Experience

* **Software Automations Engineer** — AMD EPYC *(2023)*
  * Deployed a MySQL server on an EPYC server platform for automated hardware validation.
  * Integrated an automation framework across several engineering teams.

* **Artificial Intelligence Intern** — Intel Corp. *(2022)*
  * Researched a self-supervised C/C++ code anomaly detection model.
  * Investigated additional bug-detection AI approaches and prepared a research report.

## Skills

* **Programming**: Python, C++, MATLAB
* **Deep Learning**: PyTorch, Hugging Face Transformers, OpenCV
* **Research**: Sign Language Recognition, Video Understanding, LLM integration
* **Tools**: Git, Docker, LaTeX, Linux

## Publications

  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
