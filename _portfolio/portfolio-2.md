---
title: "Autonomous Navigation & Object Localization in ROS2 (Course Project)"
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

<video width="100%" controls loop muted style="max-width: 800px;">
  <source src="/images/portfolio/597task1_edited.mp4" type="video/mp4">
</video>

---

## Task 2 — Navigation with Static Obstacles

### Key Components

Implemented a two-level navigation stack combining **A\* global planning** with **RRT local replanning** from real-time `/scan` data.

### Demo

<video width="100%" controls loop muted style="max-width: 800px;">
  <source src="/images/portfolio/597task2_edited.mp4" type="video/mp4">
</video>


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

<video width="100%" controls loop muted style="max-width: 800px;">
  <source src="/images/portfolio/597task3_output.mp4" type="video/mp4">
</video>