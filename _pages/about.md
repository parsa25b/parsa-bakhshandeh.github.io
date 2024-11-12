---
permalink: /
title: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

**About Me**
--------

I am currently a Controls Software Engineer at Sanctuary AI, where I work at the intersection of robotics hardware, control systems, simulation, and reinforcement learning. I focus on developing high- and low-level controllers with an emphasis on smooth motion, safety and compliance. 
My passion for robotics and humanoids drives my daily work, and I find great satisfaction in developing innovative solutions to improve robotic controllers. 

I come from a background in mechanical engineering, having earned my bachelor's degree from Sharif University of Technology. During my bachelor studies, I developed a deep interest in robotics and control systems, which has continued to shape my career. I also spent two years as a research assistant at the University of British Columbia, where my master's research focused on applying Digital Twin technology for monitoring and controlling CNC machining processes.


Below are some open-source projects I've worked on.

**Open Source Projects**
--------

### Robot Task Space Control [code](https://github.com/parsa25b/robot_task_space_control)
This project focuses on controlling the robot in task space using a controller that incorporates various inverse kinematics solvers, such as the Levenberg-Marquardt method and quadratic programming. The simulation engine used is MuJoCo, primarily for calculating the Jacobian. The robot environment is designed to be easily replaceable with other simulation engines, such as Drake or Pinocchio. A demonstration of the controller is provided, showcasing its application on different robots (H1 and UR5e) to control the end effector pose. Below are example video demonstrations:

![UR5e Task Space Control](https://github.com/parsa25b/parsa-bakhshandeh.github.io/blob/main/images/ur5e_task_space_control.gif?raw=true)

![h1 right arm Task Space Control](https://github.com/parsa25b/parsa-bakhshandeh.github.io/blob/main/images/h1_right_arm_task_space_control.gif?raw=true)

### VR Headset Teleoperation [code](https://github.com/parsa25b/vr_robot_control)
This project employs the oculus_reader library to capture hand poses from the Meta Quest headset, creating a user-friendly teleoperation platform. When combined with the Robot Task Space Control, this setup allows for controlling the robot's joint positions. By integrating a ROS2 interface, it can be further utilized to control the robot hardware.

### Learning Quadruped Locomotion [code](https://github.com/parsa25b/quadruped-rl-locomotion)
This project features a custom Gymnasium environment designed for training quadruped locomotion using reinforcement learning within the MuJoCo simulation engine. The cost and reward structures have been shaped for quadruped movement (although they can be improved). Below is an example offline trained model:

![trained model](https://github.com/parsa25b/parsa-bakhshandeh.github.io/blob/main/images/341280291-8afddece-8186-4b9d-8352-594dcef4d53d.gif?raw=true)

### Trajectory Profile Generation [code](https://github.com/parsa25b/trajectory_generation)
This repository features a general trajectory generation algorithm that produces an acceleration-limited (bang-bang) trajectory profile. By applying the same FIR filter multiple times, the algorithm can generate higher-order polynomial trajectories. These smooth motion profiles can then be used to control robotic actuators effectively. Below is an example of a user desired trajectory

![alt text](https://raw.githubusercontent.com/parsa25b/parsa-bakhshandeh.github.io/refs/heads/main/images/GUI_TG.JPG)


