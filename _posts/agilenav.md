---
title: "Agile Navigation"
date: 2024-04-05
layout: post
categories: [project, planning]
tags: [project]
---

# swift_nav

## Introduction
Huazhong University of Science and Technology - School of Artificial Intelligence and Automation - Coralab Lab, ROS package for *Agile and Safe Trajectory Planning for Quadruped Navigation with Motion Anisotropy Awareness*


## Framework
![System Overview](/_images/agilenav/systemoverview.png)
**Key Function**:The entire real-time navigation implementation, including: coarse path search, segmented trajectory optimization, trajectory tracking.  
`fast_navigation`:Navigation Manage  
`lazykinoprm`:Kinodynamic Trajectory Generation  
`nontrajopt`:Nonlinear Trajectory Optimization  
**Auxiliary Functions**:visualization of rviz, acquisition of navigation target points and other auxiliary functions, the following packages use open source code and partially modification.  
`grid_path_search`:https://github.com/chunyang-zhang/grid_path_searcher/  
`rviz_plugins`:  
`waypoint_generator`:https://github.com/epan-utbm/waypoint_generator  