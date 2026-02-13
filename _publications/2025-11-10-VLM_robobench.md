---
title: "AgenticLab: A Real-world Robot Agent Platform that Can See, Think, and Act"
collection: publications
permalink: /publication/2026-01-31-AgenticLab
# venue: Under Review
excerpt: '<div style="display: flex; gap: 15px; align-items: flex-start; flex-wrap: wrap;"><div style="flex: 0 0 100%; max-width: 300px;"><a href="https://drive.google.com/file/d/1IxNuYt15cYBI_d9qOa1-s4-BhJElBFpb/view?usp=drive_link" target="_blank"><video autoplay loop muted playsinline width="100%" style="border-radius: 6px; box-shadow: 0 2px 4px rgba(0,0,0,0.1);"><source src="/files/AgenticLab_teaser.mp4" type="video/mp4"></video></a></div><div style="flex: 1; min-width: 250px;"><p style="margin-bottom: 5px; font-size: 0.95em;"><b>Pengyuan Guo*</b>, Zhonghao Mai*, Zhengtong Xu*, Kaidi Zhang, Heng Zhang, Zichen Miao, Arash Ajoudani, Zachary Kingston, Qiang Qiu, Yu She</p><p style="margin-bottom: 5px; font-style: italic; color: #666;">Under Review, 2026</p><p style="font-size: 0.9em;"><a href="https://arxiv.org/pdf/2602.01662">arXiv</a> / <a href="#">website(soon)</a> / <a href="#">code(soon)</a> / <a href="/publication/2026-01-31-AgenticLab#bibtex-section">bibtex</a></p></div></div>'
date: 2026-01-31

---

## Overview

In this work, we present **AgenticLab**, an **open-source, real-world benchmark platform** that integrates large vision-language models (VLMs) and large language models (LLMs) to enable _zero-shot robotic manipulation_ through reasoning and embodied interaction.

Unlike existing simulation-based benchmarks, AgenticLab focuses on **accessible hardware**, **Open Knowledge-based Models**, and **compositional agentic intelligence**, allowing researchers to study how VLM/LLM models perform in real-world manipulation scenarios.

- <strong style="font-size: 1.2em;">[More Videos (in-the-wild)](https://drive.google.com/drive/folders/1FhkyPC2_33m97-Z4PHx9VMXpbwQS6fPe?usp=sharing)</strong>



<div id="bibtex-section" style="margin-top: 20px;">
    <h3>BibTeX</h3>
    <button onclick="copyBibtex()" class="btn btn--info" style="margin-bottom: 10px;">Copy BibTeX</button>
    <pre id="bibtex-citation" style="background-color: #f6f8fa; padding: 15px; border-radius: 5px; font-size: 0.85em; overflow-x: auto;">@misc{guo2026agenticlab,
  title={AgenticLab: A Real-World Robot Agent Platform that Can See, Think, and Act},
  author={Pengyuan Guo and Zhonghao Mai and Zhengtong Xu and Kaidi Zhang and Heng Zhang and Zichen Miao and Arash Ajoudani and Zachary Kingston and Qiang Qiu and Yu She},
  year={2026},
  eprint={2602.01662},
  archivePrefix={arXiv},
  primaryClass={cs.RO},
  url={https://arxiv.org/abs/2602.01662},
}</pre>
</div>

<script>
function copyBibtex() {
  var bibtex = document.getElementById('bibtex-citation').textContent;
  navigator.clipboard.writeText(bibtex).then(function() {
    alert('BibTeX citation copied to clipboard!');
  }, function(err) {
    console.error('Could not copy text: ', err);
  });
}
</script>