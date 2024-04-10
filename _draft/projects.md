---
layout: page
icon: fas fa-archive
order: 1
---

### [Hybrid Dynamics Modeling and Trajectory Planning for a Cable-Trailer System with a Quadruped Robot](/posts/SledNav)
<div style="border: 0px solid #1182BF;padding: 4px;">
    <p> <img class="left" src="/images/slednav/sledrobotoutdoor.jpg" width="500px" alt="sledrobotoutdoor"/> Inspired by the utilization of dogs in sled-pulling for transportation, we introduce a cable-trailer system with a quadruped robot. The motion planning of the proposed robot system presents challenges arising from the nonholonomic constraints of the trailer, system underactuation, and hybrid interaction through the cable. To tackle these challenges, we develop a hybrid dynamics model that accounts for the cable's taut/slack status. Since it is computationally intense to directly optimize the trajectory, we first propose a search algorithm to compute a sub-optimal trajectory as the initial solution. Then, a novel collision avoidance constraint based on the geometric shapes of objects is proposed to formulate the trajectory optimization problem for the hybrid system. The proposed trajectory planning method is implemented on a Unitree A1 quadruped robot with a customized cable-trailer and validated through experiments.</p>
</div>


### [Agile and Safe Trajectory Planning for Quadruped Navigation with Motion Anisotropy Awareness](/posts/AgileNav)
<div style="border: 0px solid #1182BF;padding: 4px;">
    <p> <img class="left" src="/images/agilenav/systemoverview.bmp" width="500px" alt="systemoverview"/> Quadruped robots demonstrate robust and agile movements in various terrains; however, their navigation autonomy is still insufficient. One of the challenges is that the motion capabilities of the quadruped robot are anisotropic along different directions, which significantly affects the safety of quadruped robot navigation. This paper proposes a navigation framework that takes into account the motion anisotropy of quadruped robots including kinodynamic trajectory generation, nonlinear trajectory optimization, and nonlinear model predictive control. In simulation and real robot tests, we demonstrate that our motion-anisotropy-aware navigation framework could: (1) generate more efficient trajectories and realize more agile quadruped navigation; (2) significantly improve the navigation safety in challenging scenarios. The implementation is realized as an open-source package at <a href="https://github.com/ZWT006/agile_navigation" target="_blank" >agile_navigation: Quadruped Robot Planning ROS Package (github.com)</a></p>
</div>

### [Quadruped Robot Planning Framework for Navigation, Formation, Collaboration, and Flocking](/posts/MultiAgent)
<div style="border: 0px solid #1182BF;padding: 4px;">
    <p> <img class="left" src="/images/multinav/framework.bmp" width="500px" alt="framework"/> After multiple optimization iterations, we developed and deployed the complete navigation framework, encompassing both hardware and software. The hardware is characterized by its compactness and lightweight design. Meanwhile, the software integrates perception, planning, and control functionalities, facilitating the seamless deployment of various algorithms. Several of our projects leverage this framework, spanning quadruped robot navigation, formation control, collaboration, and flocking.</p>
</div>

### [chigui: A novel Spherical Robot Drive by Barycenter Offset and Conservation of Angular Momentum](/posts/Robotchigui)
<div style="border: 0px solid #1182BF;padding: 4px;">
    <p> <img class="left" src="/images/ballbot/chigui.bmp" width="200px" alt="chigui"/> The spherical robot Chigui integrates the drive principles of Barycenter Offset (BCO) and Conservation of Angular Momentum (COAM), propelled by three motors with two reaction wheels.  Employing the Euler-Lagrange system dynamics model based on the d’Alembert principle, we analyze the robot's motion behavior and introduce three basic robot motions to simplify the dynamics model and derive equations for external torque input motion.  We design a cascade controller for the robot's basic motion and establish a ROS-Gazebo physical simulation platform for algorithm testing.  Additionally, we assemble mechanical structures, develop a hardware control system, and author embedded real-time control code for experimentation.</p>
</div>

### [Wheeled Robot for RoboMaster University Series Competition](/posts/RobotWheeled)
<div style="border: 0px solid #1182BF;padding: 4px;">
    <p> <img class="left" src="/images/rm/hero2.jpg" width="200px" alt="hero"/> The RoboMaster University Series (RMU) is a platform for robotic competitions and academic exchange, specially designed for global technology enthusiasts. It requires participants to go beyond their textbooks to form robotics teams, develop a diverse fleet of robots, and participate in team battles. I participated RMU2021 with my teammates as leader of Electric Control Group. We design schemes, make circuit boards, and debug embedded programs. We tirelessly tested and optimized our robots, and endured countless sleepless nights. It' a memorable and cherished time.</p>
</div>