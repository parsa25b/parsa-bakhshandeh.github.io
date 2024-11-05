---
permalink: /
title: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

About Me
--------

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


