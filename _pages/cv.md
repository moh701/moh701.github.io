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
* **M.S. in ICT for Internet and Multimedia**, University of Padova (Italy), 2021 - 2024
  * Focus on Machine Learning, IoT, and E-Health.
* **B.S. in Biomedical Engineering**, Azad University of Mashhad (Iran), 2011 - 2015

Work Experience
======
* **Research Assistant | University of Eindhoven (Netherlands)**
  * *April 2024 – July 2024*
  * Improved uterus image segmentation accuracy by 25% and reduced clinical misdiagnosis rates by 18%.
  * Applied Machine Learning techniques to Biomedical Imaging (DICOM data).

* **Research Assistant | University of Deusto (Spain)**
  * *October 2023 – March 2024*
  * Developed AI models for sound-based physiological flow rate extraction with 85% accuracy.
  * Specialized in SVM algorithms and signal processing for non-invasive monitoring.

Technical Skills
======
* **Programming**: Python (PyTorch, TensorFlow, Keras), C++, MATLAB.
* **AI Specialization**: Large Language Models (LLM Security, Llama-3-8B), Computer Vision, Signal Processing.
* **Tools**: OpenCV, Git, Linux, Docker, LaTeX.

Patents & Inventions
======
* **International Patent (A61C3/14)**: Digital Dental Counter. 
  * Developed a device to reduce medical extraction errors in dental schools from 20% to 5%.

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
