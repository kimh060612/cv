---
layout: page
title: Unknown Area Anticipation for Embodied Agent Navigation
description: a project with a background image and giscus comments
img: assets/img/Uncertain_Anticipate_Overview.png
importance: 2
category: study
giscus_comments: true
---

## Project Descriptions

I explore **Object-Goal Navigation (OGN)** and **Multiple Object-Goal Navigation (M-OGN)** and propose practical ideas that improve **goal-conditioned exploration** and **object-centric planning**.

In a recent study, some components did not meet target performance, but the project surfaced **actionable insights** on curriculum scheduling, sub-goal discovery, and memory for multi-goal tasks. I am conducting a **post-mortem analysis** to consolidate these findings into a more robust pipeline.

[Github Link](https://github.com/kimh060612/MultiON-VAE.git)


## Project Details

The core idea of this project is following: 

- This project departs from the idea that “**If embodied agent can anticipate the unseen area of environment, they can efficiently navigate through goal point**”
    - We proposed Conditional VAE model to anticipate unseen area of Top-Down BEV map.
    - We proposed novel reward function for agents to actively explore the unseen area.
- However, this idea fails due to reasons below:
    - We failed to collect well-define 2D Top-Down map data with given time and resources.
    - There is certain noise in MP3D dataset and we failed to deal with that.
    - To resolve this problem, we need to use more photo-realistic dataset such as Proc-THOR or HM3D.

## Materials

[Material Links](https://drive.google.com/file/d/1AIUGAnyrQfZeitUfmWJIs_LNwwiaiPUp/view?usp=sharing)

