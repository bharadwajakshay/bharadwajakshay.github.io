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
* Ph.D. in Geomatics Engineering, University of Calgary, 2026
  * Dissertation: *Cost-Effective Mapping Platform to Generate HD-Maps for Autonomous Vehicles and Digital Twins*
* M.S. in Electrical and Computer Science Engineering, Ohio University, 2018
  * Thesis: *A Perception Payload for Small-UAS Navigation in Structured Environments*
* B.E. in Medical Electronics, Visvesvaraya Technological University, India

Work experience
======
* Graduate Researcher, University of Calgary
  * Multi-sensor fusion and SLAM for autonomous navigation, 3D reconstruction, and digital twins
  * Photogrammetric self-calibration, sensor benchmarking, and learning-based LiDAR–camera calibration

* Software Engineer, Sensor Fusion — LocusLabs (acquired by Acuity Brands)
  * Developed full-stack perception and mapping systems deployed in airports and malls worldwide

* Graduate Research Assistant, Ohio University
  * Built perception payloads for small-UAS navigation in structured and GPS-denied environments

* Embedded Design Engineer — Redmount Consultancy Services
  * Designed FPGA/DSP-based imaging solutions

Skills
======
* Programming: Python, C, C++, MATLAB
* Frameworks & Tools: PyTorch, TensorFlow, ROS, Docker, AWS, LaTeX, Git
* Domains: Photogrammetry, SLAM, Sensor Fusion, Robotics, Computer Vision, 3D Reconstruction

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
