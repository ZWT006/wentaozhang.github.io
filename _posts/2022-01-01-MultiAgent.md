---
title: "Multi-Robot Systems Planning Framework"
date: 2023-09-15
layout: post
categories: [research, planning]
tags: [legged robots, multi-agent systems, motion and path planning]
---


## Introduction
After multiple optimization iterations, we developed and deployed the complete navigation framework, encompassing both hardware and software. The hardware is characterized by its compactness and lightweight design. Meanwhile, the software integrates perception, planning, and control functionalities, facilitating the seamless deployment of various algorithms. Several of our projects leverage this framework, spanning quadruped robot navigation, formation control, collaboration, and flocking.


<img class="center" src="/images/multinav/iteration.png" width="600px" alt="iteration"/>

## Framework
<img class="center" src="/images/multinav/framework.bmp" width="600px" alt="framework"/>

## Research

#### Distributed Model Predictive Formation Control with Gait Synchronization for Multiple Quadruped Robots
<div style="border: 0px solid #1182BF;padding: 4px;">
    <p> <img class="left" src="/images/multinav/Formation.jpg" width="250px" alt="Formation" /> We present a fully distributed framework for multiple quadruped robots in environments with obstacles. It is notable that all the robots are able to avoid obstacles, navigate to the desired positions, and meanwhile synchronize the gaits.</p>
</div>


#### Optimization-Based Flocking Control and MPC-Based Gait Synchronization Control for Multiple Quadruped Robots
<div style="border: 0px solid #1182BF;padding: 4px;">
    <p> <img class="left" src="/images/multinav/flocking.jpg" width="250px" alt="flocking"/> We focus on the flocking control and gait  synchronization control of multiple quadruped robots to achieve the movement during patrol tasks. To achieve these goals, we  propose an optimization-based distributed flocking controller and  a model predictive control (MPC)-based gait synchronization controller.</p>
</div>


#### Observer-based Distributed MPC for Collaborative Quadrotor-Quadruped Manipulation of a Cable-Towed Load (<font color="blue">Finalist for the IEEE-ICRA2024 Best Conference Paper Award</font>)
<div style="border: 0px solid #1182BF;padding: 4px;">
    <p> <img class="left" src="/images/multinav/Collaboration.png" width="250px" alt="Collaboration"/> We presents a collaborative quadrotor-quadruped  robot system for the manipulation of a cable-towed payload. In particular, we aim to solve the challenge from the unknown dynamics of the cable-towed payload. The proposed system is validated through challenging  field experiments in indoor and outdoor environments.</p>
</div>

<!-- #### Distributed CLF-CBF-QP for Safe Formation Control of Multi-robot System
<div style="border: 0px solid #1182BF;padding: 4px;">
    <p> <img class="left" src="/images/multinav/Formation-1.png" width="250px" alt="Formation-1"/> We explore a class of safety formation control method, where a group of robots can ensure their safety while reaching the expected formation. The desired formation can be  slightly damaged to ensure safety when facing unsafe factors (such as obstacles), and it can autonomously recover when  these factors disappear.</p>
</div> -->