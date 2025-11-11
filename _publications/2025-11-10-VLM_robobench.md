---
title: "VLM-Robobench: A VLM-powered Embodied Agent Benchmarking Platform for Robot Manipulation"
collection: publications
category: Early Version
permalink: /publication/2025-11-10-VLM_robobench
excerpt: 'This paper is under working and will be submitted by the end of Jan. 2026'
date: 2025-11-10
venue: 
slidesurl: 
paperurl: 'http://academicpages.github.io/files/paper1.pdf'
citation: '**Pengyuan Guo**, Zhonghao Mai, Zhengtong Xu, Zichen Miao, Qiang Qiu, and She Yu. _In preparation._ 2025.'
---
**Note:** Manuscript is currently In preparation

## Overview

In this work, we present **VLM-RoboBench**, an **open-source, real-world benchmark platform** that integrates large vision-language models (VLMs) and large language models (LLMs) to enable _zero-shot robotic manipulation_ through reasoning and embodied interaction.

Unlike existing simulation-based benchmarks, VLM-RoboBench focuses on **accessible hardware**, **Open Knowledge-based Models**, and **compositional agentic intelligence**, allowing researchers to study how VLM/LLM models perform in real-world manipulation scenarios.

Our system features an **agentic architecture** that unifies **symbolic reasoning**, **visual grounding**, and **low-level execution**:

- **LLM + PDDL-based task planner** with **replanning and reflection**, enabling flexible reasoning and recovery from failure.
- **VLM-guided perception and grasp reflection**, selecting between **shoulder and wrist camera views** for improved grasp understanding.
- **GraspNet-based 6D grasp pose estimation**, integrated with our **custom-designed, low-cost gripper** for robust execution.

This composition enables an embodied agent capable of **end-to-end, zero-shot manipulation** — from language goal to physical action — without any task-specific policy training.  
VLM-RoboBench thus serves as both a **research testbed** and a **benchmarking framework** for evaluating the **compositional reasoning, perception, and planning** capabilities of large-scale models in robotics.

## Demo Video
{% include video id="s1K26QrExLQ" provider="youtube" %}
{% include video id="gvgj8-u_RJY" provider="youtube" %}
{% include video id="q-HV3MPhxLs" provider="youtube" %}

## Links
- [Code Repository] (https://github.com/ZhengtongXu/vlm_robobench)

## Additional Information
- [Presentation Slides](/files/VLM_Robobench_Presentation.pdf)