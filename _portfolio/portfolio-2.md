---
title: "Autonomous Navigation \& Object Localization in ROS2 (Course Project)"
excerpt: "<em>Turtlebot3 • Gazebo • ROS2 • A* • RRT • FSM • PID • LiDAR & Vision Fusion*</em><br/><br/>Designed and implemented a fully autonomous mobile robot system capable of mapping, navigating, and localizing target objects inside an unknown indoor environment."
collection: portfolio
---

## Task 1 — Autonomous Mapping

### Key Components

- **LiDAR-based perception:** Reads `/scan` data to detect obstacles, track wall geometry, and determine free space.
- **FSM architecture:** Modular states for exploration, turning, and wall-following, allowing context-aware navigation.
- **Control system:**
  - PI controller for heading stabilization
  - Constant-speed forward motion for smooth exploration

### Demo
<!-- Add GIF file here -->
![Autonomous Mapping Demo](../images/portfolio/mapping-demo.gif)

---

## Task 2 — Navigation with Static Obstacles

### Key Components

Implemented a two-level navigation stack combining **A\* global planning** with **RRT local replanning** from real-time `/scan` data.

### Demo
<!-- Add GIF file here -->
![Navigation Demo](../images/portfolio/navigation-demo.gif)

---

## Task 3 — Search and Object Localization

### Key Components

- Built a **vision–LiDAR fusion pipeline** for object localization:
  - Color-based contour detection
  - Image-angle computation
  - LiDAR distance estimation
  - World-coordinate triangulation with RViz visualization
- Integrated a **waypoint-based patrol strategy** to search the entire map and reliably detect targets.

### Demo
<!-- Add GIF file here -->
![Object Localization Demo](../images/portfolio/localization-demo.gif)