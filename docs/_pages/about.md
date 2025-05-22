---
layout: default
title: About
permalink: /
subtitle: 

abstract: >
  abstract
intro: >
  intro
---

<div style="text-align: center; margin-top: 2rem;">
  <a href="https://arxiv.org/abs/your-arxiv-id" target="_blank" style="text-decoration: none;">
    <button style="margin: 0.5rem; padding: 0.7rem 1.2rem; font-size: 1rem; border-radius: 12px; border: none; background-color: #b31b1b; color: white;">
      📄 Paper
    </button>
  </a>
  <a href="https://github.com/youruser/yourrepo" target="_blank" style="text-decoration: none;">
    <button style="margin: 0.5rem; padding: 0.7rem 1.2rem; font-size: 1rem; border-radius: 12px; border: none; background-color: #24292e; color: white;">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" alt="GitHub" style="height: 1.2em; vertical-align: middle; margin-right: 0.5em;">
      Code
    </button>
  </a>
  <a href="https://huggingface.co/datasets/yourname/yourdataset" target="_blank" style="text-decoration: none;">
    <button style="margin: 0.5rem; padding: 0.7rem 1.2rem; font-size: 1rem; border-radius: 12px; border: none; background-color: #ffcc00; color: black;">
      <img src="https://huggingface.co/front/assets/huggingface_logo-noborder.svg" alt="HF" style="height: 1.2em; vertical-align: middle; margin-right: 0.5em;">
      Dataset
    </button>
  </a>

</div>



## Abstract

We introduce $\infty$-THOR, a new framework for long-horizon embodied tasks that advances long-context understanding in embodied AI.
$\infty$-THOR provides:
(1) a generation framework for synthesizing scalable, reproducible, and unlimited long-horizon trajectories;
(2) a novel embodied QA task, Needle(s) in the Embodied Haystack, where multiple scattered clues across extended trajectories test agents’ long-context reasoning ability; and
(3) a long-horizon dataset and benchmark suite featuring complex tasks that span hundreds of environment steps, each paired with ground-truth action sequences.
To enable this capability, we explore architectural adaptations, including interleaved Goal-State-Action modeling, context extension techniques, and Context Parallelism, to equip LLM-based agents for extreme long-context reasoning and interaction.
Experimental results and analyses highlight the challenges posed by our benchmark and provide insights into training strategies and model behaviors under long-horizon conditions.
Our work provides a foundation for the next generation of embodied AI systems capable of robust, long-term reasoning and planning.