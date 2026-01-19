---
title: "AgenticLab: A Real-world Robot Agent Platform that Can See, Think, and Act"
collection: publications
category: Early Version
permalink: /publication/2026-01-31-AgenticLab
excerpt: 'This paper is in preparation and will be submitted by the end of Jan. 2026.<br/><a href="https://drive.google.com/file/d/106X8EPDbHOG4KoH5MGcz5OQ0jq4PcfTq/view?usp=sharing" target="_blank"><img src="/files/AgenticLab_Appearance.JPG" alt="AgenticLab Hardware Platform" style="width: 100%; max-width: 400px; border-radius: 8px;"></a>'
date: 2026-01-31
# venue:
slidesurl: 
# paperurl: 'http://academicpages.github.io/files/paper1.pdf'
citation: '<strong>Pengyuan Guo</strong>, Zhonghao Mai, Zhengtong Xu, Zichen Miao, Qiang Qiu, and She Yu. <em>In preparation.</em> 2026.'
---
**Note:** Manuscript is currently In preparation

## Overview

In this work, we present **AgenticLab**, an **open-source, real-world benchmark platform** that integrates large vision-language models (VLMs) and large language models (LLMs) to enable _zero-shot robotic manipulation_ through reasoning and embodied interaction.

Unlike existing simulation-based benchmarks, VLM-RoboBench focuses on **accessible hardware**, **Open Knowledge-based Models**, and **compositional agentic intelligence**, allowing researchers to study how VLM/LLM models perform in real-world manipulation scenarios.

Our system features an agentic architecture that unifies symbolic reasoning, visual grounding, and low-level execution:

- **LLM + PDDL-based task planner** with **replanning and reflection**, enabling flexible reasoning and recovery from failure.
- **VLM-guided perception and grasp reflection**, selecting between shoulder and wrist camera views for improved grasp understanding.
- **GraspNet-based 6D grasp pose estimation**, integrated with our custom-designed, low-cost gripper for robust execution.

This composition enables an embodied agent capable of end-to-end, zero-shot manipulation — from language goal to physical action — without any task-specific policy training.  
VLM-RoboBench thus serves as both a research testbed and a benchmarking framework for evaluating the compositional reasoning, perception, and planning capabilities of large-scale models in robotics.

## Demo Videos

**Demo 1**
<iframe width="560" height="315" src="https://www.youtube.com/embed/s1K26QrExLQ" frameborder="0" allowfullscreen style="max-width: 100%;"></iframe>

**Demo 2**
<iframe width="560" height="315" src="https://www.youtube.com/embed/gvgj8-u_RJY" frameborder="0" allowfullscreen style="max-width: 100%;"></iframe>

**Demo 3**
<iframe width="560" height="315" src="https://www.youtube.com/embed/q-HV3MPhxLs" frameborder="0" allowfullscreen style="max-width: 100%;"></iframe>

<br>

- <strong style="font-size: 1.2em;">[More Videos (in-the-wild)](https://drive.google.com/drive/folders/1FhkyPC2_33m97-Z4PHx9VMXpbwQS6fPe?usp=sharing)</strong>

## Links
- [Code Repository](https://github.com/ZhengtongXu/vlm_robobench)

## Additional Information
- [Presentation Slides](/files/VLM_Robobench_Presentation.pdf)