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
* **M.S. in Computer Science**, Soongsil University, Seoul, South Korea *(Expected Aug 2025)*
  * GPA: 4.16 / 4.5
  * Researcher at System Software Lab under Prof. Jaeyong Choi
  * Thesis: *Diffusion-Driven Image Generation with Disentangled Style and Structure-Aware Fidelity*
* **B.E. in Software Engineering**, Mehran University of Engineering and Technology, Pakistan *(2018–2023)*
  * GPA: 3.73 / 4.0
  * Graduated as the top student in the class
  * Final Year Project: Real-Time Face Recognition Attendance System Using Computer Vision

Research Experience
======
* **Graduate Researcher**, System Software Lab, Soongsil University *(Sep 2023 – Present)*
  * Developing diffusion-based generative models for multilingual font synthesis (Korean, Chinese, Latin).
  * Designing multi-scale style injection, CLIP-guided losses, and Sobel structural constraints.
  * Published at ICOIN 2025; extended work under journal review at MDPI Electronics.

* **Teaching Assistant**, Soongsil University *(Fall 2023)*
  * Supported the "Deep Learning Programming" graduate course.
  * Prepared lab materials on PyTorch, CNNs, and model evaluation.

* **Visiting Lecturer**, KOICA Programme, Soongsil University *(Sep 2024)*
  * Delivered fast-track ML/AI module for KOICA scholars: ML basics, deep-learning labs, CV & diffusion demos, AI ethics.
  * Mentored capstone teams to deploy real-world ML solutions.

Skills
======
* **Deep Learning Frameworks:** PyTorch, TensorFlow, Keras
* **Languages:** Python (fluent), C++ (basic), HTML/CSS
* **ML Tools:** HuggingFace Diffusers, VGG Feature Extractors, OpenCV, NumPy
* **Model Types:** Diffusion Models, GANs, Style Encoders, CNNs
* **Data Tools:** Pandas, Matplotlib, Jupyter, Weights & Biases
* **Other Tools:** Git, Docker, Linux, LaTeX

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Awards & Honors
======
* Top graduating student — B.E. Software Engineering, Mehran University (2023)
* ICOIN 2025 — Accepted conference paper on diffusion-based Korean font generation
* MDPI Electronics — Journal paper accepted on positional-component-guided Hangul generation (2025)
