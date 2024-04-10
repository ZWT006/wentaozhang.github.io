---
title: "Spherical Robotic chigui"
date: 2022-06-31
layout: post
categories: [research, robotics]
tags: [nonholonomic motion planning, underactuated robots, optimization and optimal control]
---

## Introduction
The spherical robot Chigui integrates the drive principles of Barycenter Offset (BCO) and Conservation of Angular Momentum (COAM), propelled by three motors with two reaction wheels.  Employing the Euler-Lagrange system dynamics model based on the d’Alembert principle, we analyze the robot's motion behavior and introduce three basic robot motions to simplify the dynamics model and derive equations for external torque input motion.  We design a cascade controller for the robot's basic motion and establish a ROS-Gazebo physical simulation platform for algorithm testing.  Additionally, we assemble mechanical structures, develop a hardware control system, and author embedded real-time control code for experimentation.

## Mechanical Structure, Modeling and Control
![Ctrl](/images/ballbot/chiguiCtrl.bmp)
![Iteration](/images/ballbot/chiguiIteration.bmp)


## Conclusion
In real-world testing, the robot's basic motions align with theoretical analysis, demonstrating the controller's ability to drive the robot through these motions, with the potential for complex motion combinations.  Future endeavors will concentrate on refining motion control precision, including optimizing the dynamic model, analyzing nonlinear control system intricacies, and devising trajectory planning methods with dynamic constraints.
