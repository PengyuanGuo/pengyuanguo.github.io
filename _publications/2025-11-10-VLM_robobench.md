---
title: "AgenticLab: a Real-world Robot Agent Platform that Can See, Think, and Act"
collection: publications
category: Early Version
permalink: /publication/2025-11-10-VLM_robobench
excerpt: 'This paper is in preparation and will be submitted by the end of Jan. 2026.<br/><a href="https://youtube.com/shorts/fBgpLC1gsh0" target="_blank"><img src="https://img.youtube.com/vi/fBgpLC1gsh0/hqdefault.jpg" alt="Block Stacking Task with VLM Agent" style="width: 100%; max-width: 400px; border-radius: 8px;"></a>'
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
<div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 20px; align-items: start;">

  <div>
    <h3 style="margin: 0 0 10px 0;">Demo 1</h3>
    <div style="position:relative; width:100%; padding-top:56.25%;">
      <iframe src="https://www.youtube.com/embed/s1K26QrExLQ" 
              style="position:absolute; top:0; left:0; width:100%; height:100%;" 
              frameborder="0" allowfullscreen></iframe>
    </div>
  </div>

  <div>
    <h3 style="margin: 0 0 10px 0;">Demo 2</h3>
    <div style="position:relative; width:100%; padding-top:56.25%;">
      <iframe src="https://www.youtube.com/embed/gvgj8-u_RJY" 
              style="position:absolute; top:0; left:0; width:100%; height:100%;" 
              frameborder="0" allowfullscreen></iframe>
    </div>
  </div>

  <div>
    <h3 style="margin: 0 0 10px 0;">Demo 3</h3>
    <div style="position:relative; width:100%; padding-top:56.25%;">
      <iframe src="https://www.youtube.com/embed/q-HV3MPhxLs" 
              style="position:absolute; top:0; left:0; width:100%; height:100%;" 
              frameborder="0" allowfullscreen></iframe>
    </div>
  </div>

</div>


## Links
- [Code Repository](https://github.com/ZhengtongXu/vlm_robobench)

## Additional Information
- [Presentation Slides](/files/VLM_Robobench_Presentation.pdf)