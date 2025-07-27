---
title: "Battery-Constrained Single-Agent Exploration"
collection: projects
permalink: /projects/battery-optimization
excerpt: 'Reinforcement Learning for battery-aware single-agent exploration in grid-based environments using WindyGridWorld and DDPG.'
date: 2024-12-10
image: 
  path: &image /images/battery-exploration.jpg
  teaser: /images/battery-exploration-teaser.jpg
  caption: "Battery-aware exploration in dynamic gridworld environments"
---

## Project Overview
This project focuses on intelligent exploration in resource-constrained environments using a battery-aware single-agent. Built on a modified WindyGridWorld environment, the agent learns to maximize coverage while avoiding energy depletion using DDPG.

## Technologies Used
- **Python** (Gym-like custom environments)
- **Reinforcement Learning:** DDPG
- **Battery-Constrained Planning**
- **Matplotlib** for visualization

## Key Features
- Continuous state and action space
- Reward shaping for battery consumption
- Dynamic environment with stochasticity
- Custom visualization of coverage and battery use

## Research Contributions
- Novel reward formulation incorporating battery limits
- Evaluation of DDPG performance in sparse reward exploration tasks
- Potential extension to multi-agent systems

## Video Demo
<div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%; margin: 20px 0;">
  <iframe src="https://www.youtube.com/embed/TS02ACSNanM?autoplay=1&mute=1" 
          style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; border: 0;" 
          allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
          allowfullscreen>
  </iframe>
</div>

## GitHub
- [Battery Optimization Project](https://github.com/hxriharan/Battery-Optimization-Single-Agent-Exploration)
