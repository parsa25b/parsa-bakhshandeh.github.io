---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}


Work Experience
---------------

* Sanctuary AI
  * Senior Controls Engineer (September 2024 – Present)
    * Developed whole body controller stack using optimization based method (QP)
    * Enhanced robot safety and smooth motion by incorporating gravity compensation in the control loop, leading to decreased PD gains.
    * Implemented a low-cost, easy-to-set-up robot teleoperation system using the Quest Meta headset
    * Built a Python-based validation tool for robotic actuators, combining multiple test profiles to automate system readiness checks.
    

  * Controls Software Engineer (March 2023 2024 – September 2024)
    * Engineered a trajectory smoothing algorithm in C++ and Python that respects robot kinematic limits while ensuring low latency.
    * Proficient in DDS and ROS2 for communication.
    * Experienced with EtherCAT, adding Rx and Tx objects 
    * Contributed to development of multiple user interfaces for daily robot operations in C++ with ImGui and QT
    * Vibration analysis of robot end-effector using IMU sensors and motion capture markers

* University of British Columbia

  * Research Assitant (September 2020 – January 2023)
    * Developed a MATLAB-based digital twin software application for monitoring and controlling of CNC machining systems
    * Implemented motion planning for CNC machines using FIR filter
    * Estimated cutting force at the tooltip in machining applications using hammer test and Kalman Filter
  
  * Teaching Assistant (Septemeber 2021 - Decemeber 2022)
    * Supervised students in Computer Control of Mechatronics Systems, Mechanical Vibrations, and Machine Design Courses


Education
---------

* Master of Applied Science in Mechanical Engineering, The University of British Columbia, Vancouver, Canada
  September 2020 — December 2022
  * Thesis: Digital twin assisted process monitoring and control, Supervised by Professor Yusuf Altintas This thesis demonstrates how machining simulations can integrate CNC-derived data from sound, vibration, and force sensors, enabling the creation of a digital twin that detects chatter, tool breakage, and tool wear in CNC applications.

* Bachelor of Science in Mechanical Engineering, Sharif University of Technology, Tehran, Iran
  September 2016 — July 2020
  * Thesis: Suppression of undesirable chatter vibrations in nonlinear machining process by vibration absorber This thesis presents a technique to mitigate chatter vibrations in CNC machines through the incorporation of a passive vibration absorber system consisting of mass-spring-damper elements.
  Structural Engineering of Industrial Facilities Summer School at North Rhine-Westphalia Technical University, Aachen, Germany


Skills
======
* Python: NumPy, Pandas, OSQP, MuJoCo, Drake, PyTorch, and Gymnasium
* C++
* bash
* ROS2 and DDS
* CI/CD, Dev containers

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  