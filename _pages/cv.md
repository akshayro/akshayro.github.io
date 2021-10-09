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
* BSE in Computer Engineering, University of Michigan (Ann Arbor), 2020
* MSE in Biomedical Engineering, University of Michigan (Ann Arbor), 2021

Research experience
======
* 12/2019 – Present | Master's Researcher | U-M Restorative Neuroengineering Group
  * Applying signal-processing and machine-learning methods to improve the efficacy of subthalamic deep brain stimulation (STN-DBS) surgeries for treating the motor symptoms of Parkinson’s disease.
  * Programming neuromodulation equipment used during surgery to record electrophysiological data from patients (LabVIEW).
  * Supervisor: Parag Patil, MD, PhD

* 09/2017 – 09/2019 | Undergraduate researcher | U-M Ultrasound Therapy Lab
  * Investigated the physics of histotripsy: non-invasive therapy that uses focused ultrasound to ablate tissue
  * Analyzed acoustic data from ultrasound transducers/receivers to measure the energy efficiency of histotripsy therapies (MATLAB). Worked extensively with ultrasound transducer hardware, FPGA microcontrollers (Verilog, C), and networking equipment (Python).
  * Supervisor: Zhen Xu, PhD
  
Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
