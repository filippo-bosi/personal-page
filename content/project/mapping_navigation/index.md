---
title: Mapping and Navigation for a Robot Waiter
summary: This project implements mapping and navigation algorithms for a simulated robot waiter in a coffee shop environment. Here, Probabilistic Roadmap (PRM) and Adaptive Monte Carlo Localization (AMCL), along with the Robot Operating System (ROS) and Gazebo simulation, are used to solve different tasks. The TurtleBot3 robot, equipped with a laser distance sensor and camera module, is used for validation. Mapping involves teleoperation and frontier-based exploration, generating binary occupancy maps in MATLAB. Localization is performed using a particle filter, and navigation includes evaluating ROS2 Nav2 and implementing a PRM planner in MATLAB.
tags:
  - Mobile Robots
  - Motion Planning
date: '2023-06-01T00:00:00Z'

# Optional external URL for project (replaces project detail page).
# external_link: ''

image:
  caption: Adaptive Monte Carlo Localization (AMCL)
  focal_point: Smart

links:
  - icon: pdf-solid
    name: Paper
    url: 'https://drive.google.com/file/d/1UIl7tiNhj9kDIb1ifatpipaPoLxsXANC/view'
  - icon: youtube
    icon_pack: fab
    name: YouTube
    url: 'https://www.youtube.com/watch?v=1bvKjuoLdVE'

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

*Abstract*—This project presents the mapping and navigation of a simulated robot waiter in a coffee shop environment. The main objective is to implement mapping and navigation algorithms using Probabilistic Roadmap (PRM) and Adaptive Monte Carlo Localization (AMCL). The Robot Operating System (ROS) and Gazebo simulation environment are utilized for its development.
Using the TurtleBot3 robot equipped with a laser distance sensor and a camera module for simulation validation. The mapping process involves two methods: teleoperation and frontier-based
exploration. The obtained maps are transformed into binary occupancy maps using MATLAB. A particle filter is applied to localize the robot’s initial position using sensor data and the map.
For navigation, two approaches are explored: using the ROS2 Nav2 package for evaluation and implementing a PRM planner in MATLAB. The PRM planner connects the initial and target positions on the free configuration space by generating random configurations and validating collision-free paths. The results demonstrate successful mapping, localization, and navigation of the robot waiter in the coffee shop environment. The presented approach provides insights into the application of Monte Carlo Localization and Probabilistic Roadmap algorithms for mobile robotics.
{style="text-align: justify;"}

![alt nav2 ROS](nav2.png)

**Skills**: Mobile Robotics · Robot Operating System (ROS) · ROS2 · Ubuntu · Gazebo · MATLAB