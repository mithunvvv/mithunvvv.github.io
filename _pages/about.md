---
permalink: /
title: "Mithun Vanniasinghe"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hi, I'm Mithun Vanniasinghe. I am an undergraduate student in the [Engineering Science](https://engsci.utoronto.ca/program/what-is-engsci/) program at the University of Toronto majoring in Machine Intelligence and minoring in Robotics. 

I am currently in my **final year** of undergraduate studies, focusing on all things **reinforcement learning (RL), control theory, and robotics**.  
For my undergraduate thesis, I’m exploring how to integrate **representation learning** with **Hamilton-Jacobi reachability analysis**, supervised by [Nick Rhinehart](https://leaf.utias.utoronto.ca/).  
I also spend time as a **Teaching Assistant** for first-year **Linear Algebra** (I love teaching — and linear algebra :D).


## Research Experience {#research-experience}

**Summer 2025 — Human-Robot Social Navigation (UTIAS)**  
This past summer, I was co-supervised by [Nick Rhinehart](https://leaf.utias.utoronto.ca/) and [Tim Barfoot](http://asrl.utias.utoronto.ca/~tdb/) on a project involving **imitation learning for human-robot social navigation**.  
It was my first project working with real hardware and performing real “in-the-wild” experiments. I learned an incredible amount — and even got a paper out of it!  
🎥 [Watch the project video here](https://www.youtube.com/watch?v=tOdLTXsaYLQ)

**2023–2024 — Applied Machine Learning Engineer (Tenstorrent)**  
I completed my **Professional Experience Year (PEY) Co-op** at [Tenstorrent](https://tenstorrent.com/), where I worked as an **Applied Machine Learning Engineer** focusing on **optimizing LLMs** and analyzing their **performance on Tenstorrent hardware**.  

At the same time, I was an **undergraduate ML researcher** at the [Dynamic Optimization and Reinforcement Learning Lab](https://cglee.mie.utoronto.ca/research-lab/) at UofT, supervised by [Chi-Guhn Lee](https://cglee.mie.utoronto.ca/).  
During this time, I also initiated a **collaborative project** with [Jiayu Chen](https://agentic-intelligence-lab.org/members/jiayu-chen.html) at **Hong Kong University**, working on **interpretable hierarchical imitation learning**.

**2022–2023 — Machine Learning for Experimental Physics (SuperCDMS)**  
Previously, I worked as a researcher at the [Super Cryogenic Dark Matter Search](https://supercdms.slac.stanford.edu/) (**SuperCDMS**) international collaboration, developing **machine learning techniques and tools** for experimental setups at the **University of British Columbia**.
g experimental techniques and tools at the University of British Columbia. 

## Education {#education}

- **University of Toronto**  
  *Bachelor of Applied Science (BASc), [Engineering Science](https://engsci.utoronto.ca/program/what-is-engsci/)*  
  *Major: [Machine Intelligence](https://engsci.utoronto.ca/program/majors/machine-intelligence/) · Minor: [Robotics] (https://undergrad.engineering.utoronto.ca/academics-registration/engineering-minors-certificates/robotics-mechatronics-minor/) *  


## Research Interests {#research-interests}

I am passionate about exploring various areas in technology and science. My primary research interests include:

- **Reinforcement Learning**
- **Optimal and Safe Control**
- **Imitation Learning**
- **Robotics**

I am particularly interested in how these fields intersect to create safer autonomous systems. I am interested in the theoreitcal foundations of buidling safe, autonmous systems, and especially currently interested in the field of reachability analysis. 

## Publications {#publications}

Here are my current publications that are in progress:

1. **Ratatouille: Offline Imitation Learning for Real-World Social Robot Navigations**  
   *Status*: Second author, submitted to ICRA 2026  

   *Description*: Scaling reinforcement learning for real-world social robot navigation is challenging due to safety and data limitations. Ratatouille introduces an offline imitation learning (IL) pipeline and architecture that achieves a 6× reduction in collisions per meter and a 3× improvement in success rate over naïve behavior cloning—without collecting new data. Trained entirely from expert demonstrations, Ratatouille demonstrates robust, collision-free navigation in both simulation and real-world environments, including a dense university campus and a public food court.

   I contributed extensively to hardware experimentation and real-world testing, including conducting in-the-wild navigation trials with pedestrians and resolving complex multi-device compute distribution between on-board and off-board systems via ROS communication.


2. **Offline Discovery of Interpretable Skills from Multi-Task Trajectories**  
   *Status*: Co-first author, submitted to ICRA 2026  

   *Description*: We introduce LOKI, a hierarchical imitation learning framework for discovering reusable and interpretable skills from long-horizon, multi-task offline data—without explicit rewards or subtask labels. LOKI performs two-stage skill discovery, first segmenting demonstrations into coarse, task-aware chunks using a Vector-Quantized VAE with weak supervision, then refining these segments through self-supervised sequence modeling and clustering. The discovered skill boundaries are used to construct a hierarchical policy with learned option termination conditions, enabling precise and compositional behavior control. On the D4RL Kitchen benchmark, LOKI surpasses standard baselines while uncovering semantically meaningful, human-interpretable skills.

   I initiated the core idea of combining extrinsic and intrinsic objectives for offline skill discovery and was heavily involved in building the codebase and conducting the initial experiments that established the framework’s foundation.

3. **Rapid Creation of Synthetic Data for Analysis of Dark Matter Data with Generative Adversarial Networks**  
   *Status*: In Progress (for submission to NIMA early 2025)  

   *Description*: Explores the use of Generative Adversarial Networks (GANs) to quickly generate salt (fake data) for dark matter analyses. One of the primary challenges of salting in experiments like SuperCDMS is the time-consuming nature of generating sufficient salt. The research presented aims to overcome this limitation and optimize the salting process.
