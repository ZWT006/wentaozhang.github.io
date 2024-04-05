---
# the default layout is 'page'
icon: fas fa-info-circle
order: 4
---

> Add Markdown syntax content to file `_tabs/about.md`{: .filepath } and it will show up on this page.
{: .prompt-tip }

Agile Navigation Project`_posts/agilenav.md`{_posts/agilenav.md}

# swift_nav

## Introduction
Huazhong University of Science and Technology - School of Artificial Intelligence and Automation - Coralab Lab, ROS package for *Agile and Safe Trajectory Planning for Quadruped Navigation with Motion Anisotropy Awareness*


## Framework
![System Overview](/images/agilenav/systemoverview.bmp)
**Key Function**:The entire real-time navigation implementation, including: coarse path search, segmented trajectory optimization, trajectory tracking.  
`fast_navigation`:Navigation Manage  
`lazykinoprm`:Kinodynamic Trajectory Generation  
`nontrajopt`:Nonlinear Trajectory Optimization  
**Auxiliary Functions**:visualization of rviz, acquisition of navigation target points and other auxiliary functions, the following packages use open source code and partially modification.  
`grid_path_search`:https://github.com/chunyang-zhang/grid_path_searcher/  
`rviz_plugins`:  
`waypoint_generator`:https://github.com/epan-utbm/waypoint_generator 