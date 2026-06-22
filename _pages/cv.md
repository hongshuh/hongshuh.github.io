---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Hongshuo Huang is an interdisciplinary researcher working across **materials science, mechanical engineering, computational physics, high-performance computing, and machine learning**. His work focuses on building AI systems that accelerate materials discovery — from phase-field simulation and density functional theory to transformer models and agentic LLM frameworks.

Education
======
* Ph.D. in Mechanical Engineering, University of Michigan, Ann Arbor (2024 – present)
  * Advisor: Prof. Venkat Viswanathan
* M.S. in AI Engineering (Materials), Carnegie Mellon University (2022 – 2024)
  * Mechanical and AI Lab — Advisor: Prof. Amir Barati Farimani
* B.S. in Materials Science and Engineering, Guangdong Technion–Israel Institute of Technology (2018 – 2022)
  * Advisor: Prof. Nan Wang

Research Experience
======
* **Graduate Research Assistant**, Viswanathan Group, University of Michigan (2024 – present)
  * Develop agentic, multi-agent LLM frameworks that plan and execute first-principles materials simulations.
  * Co-authored DREAMS, a DFT-based research engine coupling an LLM planner with agents for structure generation, convergence testing, and HPC scheduling.

* **Graduate Researcher**, Mechanical and AI Lab, Carnegie Mellon University (2022 – 2024)
  * Built transformer and language-model approaches for interpretable materials property prediction (MatInFormer).
  * Developed pretraining strategies for structure-agnostic property prediction and multimodal heat-capacity modeling.

* **Undergraduate Researcher**, Prof. Nan Wang's Group, Guangdong Technion–Israel Institute of Technology (2020 – 2022)
  * Developed a phase-field model for binary-alloy solidification.
  * Accelerated simulations using MPI-based parallel computing on high-performance clusters.

Skills
======
* **Machine Learning & AI**: Transformers, large language models, graph neural networks, agentic / multi-agent systems, PyTorch
* **Computational Materials Science**: Density functional theory (DFT), phase-field modeling, high-throughput screening
* **High-Performance Computing**: MPI, parallel computing, scalable simulation workflows, HPC job scheduling
* **Programming**: Python, C/C++, Git, Linux

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
