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

<div class="text-center my-5">

  <!-- Author Names (Linked) -->
  <div style="font-size: 1.1rem; margin-bottom: 0.5rem;">
    <a href="http://bosung.github.io/" target="_blank">Bosung Kim</a> and
    <a href="https://prithvirajva.com" target="_blank">Prithviraj Ammanabrolu</a>
  </div>

  <!-- Affiliation -->
  <div style="font-size: 1rem; color: #555;">
    UC San Diego
  </div>
</div>

<div style="text-align: center; margin-top: 2rem;">
  <a href="https://arxiv.org/pdf/2505.16928" target="_blank" style="text-decoration: none;">
    <button style="margin: 0.5rem; padding: 0.7rem 1.2rem; font-size: 1rem; border-radius: 12px; border: none; background-color: #b31b1b; color: white;">
      📄 Paper
    </button>
  </a>
  <a href="https://github.com/pearls-lab/infini-thor" target="_blank" style="text-decoration: none;">
    <button style="margin: 0.5rem; padding: 0.7rem 1.2rem; font-size: 1rem; border-radius: 12px; border: none; background-color: #24292e; color: white;">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" alt="GitHub" style="height: 1.2em; vertical-align: middle; margin-right: 0.5em;">
      Code
    </button>
  </a>
  <a href="https://huggingface.co/datasets/PEARLS-Lab/infini-thor" target="_blank" style="text-decoration: none;">
    <button style="margin: 0.5rem; padding: 0.7rem 1.2rem; font-size: 1rem; border-radius: 12px; border: none; background-color: #ffcc00; color: black;">
      <img src="https://huggingface.co/front/assets/huggingface_logo-noborder.svg" alt="HF" style="height: 1.2em; vertical-align: middle; margin-right: 0.5em;">
      Dataset
    </button>
  </a>
</div>


<header class="post-header">
  <h1 class="post-title">
   <span class="font-weight-bold">\(\infty\)</span>-THOR: Beyond the Needle(s) in the Embodied Haystack
  </h1>
</header>

<div class="text-center my-5">
  <h3 style="font-size: 2.0rem; font-weight: bold;">Demo Video</h3>

  <video controls style="max-width: 800px; width: 100%; margin: 0 auto; display: block;">
    <source src="assets/video/intro_vid.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>
</div>

<div class="text-center my-5">
  <h3 style="font-size: 2.0rem; font-weight: bold;">
    Abstract
  </h3>
  <p class="abstract-text">
  We introduce <span>\(\infty\)</span>-THOR, a new framework for long-horizon embodied tasks that advances long-context understanding in embodied AI.
<span>\(\infty\)</span>-THOR provides:
(1) a generation framework for synthesizing scalable, reproducible, and unlimited long-horizon trajectories;
(2) a novel embodied QA task, Needle(s) in the Embodied Haystack, where multiple scattered clues across extended trajectories test agents’ long-context reasoning ability; and
(3) a long-horizon dataset and benchmark suite featuring complex tasks that span hundreds of environment steps, each paired with ground-truth action sequences.
To enable this capability, we explore architectural adaptations, including interleaved Goal-State-Action modeling, context extension techniques, and Context Parallelism, to equip LLM-based agents for extreme long-context reasoning and interaction.
Experimental results and analyses highlight the challenges posed by our benchmark and provide insights into training strategies and model behaviors under long-horizon conditions.
Our work provides a foundation for the next generation of embodied AI systems capable of robust, long-term reasoning and planning.
</p>
</div>

<div class="text-center my-5">
  <h3 style="font-size: 2.0rem; font-weight: bold;">Needle(s) in the Emboded Haystack</h3>
  <h3>Needle(s) in the Emboded Haystack</h3>

  <figure style="max-width: 1200px; margin: 0 auto 40px; text-align: center;">
    <img src="assets/img/example_NiEH.png" alt="First Image" style="width: 100%; height: auto; display: block; margin: 0 auto;">
    <figcaption style="margin-top: 10px; font-size: 0.95rem; color: #555;">
      Figure 1: Example of Needle in the Embodied Haystack: Single-evidence question types.
    </figcaption>
  </figure>

  <figure style="max-width: 1200px; margin: 0 auto; text-align: center;">
    <img src="assets/img/example_NiSSSEH.png" alt="Second Image" style="width: 100%; height: auto; display: block; margin: 0 auto;">
    <figcaption style="margin-top: 10px; font-size: 0.95rem; color: #555;">
      Figure 2: Example of Needles in the Embodied Haystack: Multi-evidence question types.
    </figcaption>
  </figure>
</div>


<div class="text-center my-5">
  <h3 style="font-size: 2.0rem; font-weight: bold;">Long-horizon Trajectories for Interactive Evaluations</h3>
  <h3>Long-horizon Trajectories for Interactive Evaluations</h3>

  <figure style="max-width: 1200px; margin: 0 auto 40px; text-align: center;">
    <img src="assets/img/long-horizon.png" alt="First Image" style="width: 100%; height: auto; display: block; margin: 0 auto;">
    <figcaption style="margin-top: 10px; font-size: 0.95rem; color: #555;">
      Figure 3: Example of the trajectory and a long-horizon embodied task generated from <span>\(\infty\)</span>-THOR. The
final goal (“Put the tomato on the counter top” at t=670) requires recalling both the tomato (seen at
t=17) and the counter (seen at t=560) to solved the long-horizon task. Context size refers to the input
token length when converting the trajectory into the LLM input space.
    </figcaption>
  </figure>

</div>