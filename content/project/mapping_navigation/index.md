---
title: Mapping and Navigation for a Robot Waiter
summary: This project implements mapping and navigation algorithms for a simulated robot waiter in a coffee shop environment.
tags:
  - Mobile Robots
  - Motion Planning
date: '2023-06-01T00:00:00Z'

# Optional external URL for project (replaces project detail page).
# external_link: ''

image:
  caption: Adaptive Monte Carlo Localization (AMCL)
  focal_point: Smart

url_code: ''
url_pdf: 'https://drive.google.com/file/d/1UIl7tiNhj9kDIb1ifatpipaPoLxsXANC/view'
url_video: 'https://www.youtube.com/watch?v=1bvKjuoLdVE'

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

Here, Probabilistic Roadmap (PRM) and Adaptive Monte Carlo Localization (AMCL), along with the Robot Operating System (ROS) and Gazebo simulation, are used to solve the tasks. The TurtleBot3 robot, equipped with a laser distance sensor and camera module, is used for validation. Mapping involves teleoperation and frontier-based exploration, generating binary occupancy maps in MATLAB. Localization is performed using a particle filter, and navigation includes evaluating ROS2 Nav2 and implementing a PRM planner in MATLAB.

![alt nav2 ROS](nav2.png)

**Skills**: Mobile Robotics · Robot Operating System (ROS) · ROS2 · Ubuntu · Gazebo · MATLAB