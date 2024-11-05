---
permalink: /
title: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

About Me
========

I am currently a Controls Engineer at Sanctuary AI, where I work at the cutting edge of robotics hardware, simulation, and reinforcement learning. In this role, I have contributed to the development of the controller stack for Sanctuary’s humanoid robots.

Before joining Sanctuary AI, I spent two years as a research assistant at the University of British Columbia, where my master's research focused on applying Digital Twin technology for monitoring CNC machining processes. This experience provided me with a strong foundation in integrating advanced technologies with practical applications.

I earned my bachelor's degree from Sharif University of Technology, where I developed a passion for robotics and control systems that continues to drive my work today.

Open Source Projects
--------

### Robot Task Space Control
This project focuses on controlling the robot in task space using a controller that incorporates various inverse kinematics solvers, such as the Levenberg-Marquardt method and quadratic programming. The simulation engine used is MuJoCo, primarily for calculating the Jacobian. The robot environment is designed to be easily replaceable with other simulation engines, such as Drake or Pinocchio. A demonstration of the controller is provided, showcasing its application on different robots (H1 and UR5e) to control the end effector pose.

### VR Headset Teleoperation
This project employs the Oculus Reader library to capture hand poses from the Meta Quest headset, creating a user-friendly teleoperation platform. When combined with the Robot Task Space Control, this setup allows for controlling the robot's joint positions. By integrating a ROS2 interface, it can be further utilized to control the robot hardware.

### Learning Quadruped Locomotion
This project features a custom Gymnasium environment designed for training quadruped locomotion using reinforcement learning within the MuJoCo simulation engine. The cost and reward structures are specifically tailored for quadruped movement, though they can also be adapted for bipedal locomotion.

### Trajectory Profile Generation
This repository contains a general trajectory generation algorithm optimized for real-time performance with minimal computational overhead. The output trajectory profile is acceleration-limited (bang-bang trajectory), and by applying the same FIR filter again, it can produce higher-order polynomial trajectories.


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


