---
layout: page
title: HARMONIC-AI
description: Ultra-lightweight AI for Harmonic Management in Electric Grids
# changhong
# 2025 12 16
# update logo
img: assets/img/HarmonicAI.png
importance: 1
category: Funded
related_publications: false
---
## Overview
[Harmonic-AI](https://www.seai.ie/seai-research/research-database/research-projects/details/harmonicai--harmonic-management-with-ai-for-networks-to-intelligently-enhance-ev-charging-and-gridtied-microgeneration-at-customer-sites) explores the design of novel embedded detection, management and control schemes for limiting the harmonic components injected into the electricity grid from high-power EV charging infrastructure and distributed energy resources. This joint project between RCSL (TCD) and TU Dublin is funded by the Sustainable Energy Authority of Ireland (SEAI). As the TCD lead, we aim to develop efficient and lightweight deep learning models to estimate harmonic components at each node (in a distributed fashion and also at an aggregate level) and provide optimisation strategies to mitigate their effect on the grid. The research team at TUD will develop intelligent controllers that can deploy these optimisations at different levels of granularity. TCD work packages are being developed by [Changhong Li](), PhD candidate, who joined our team in April 2025. 

![HarmonicAIDemo](/assets/img/HarmonicAIDemo.png)

## News
- 2025/11/05: Paper LogicSparse accepted by ICFPT 2025.
- 2025/09/16: Kick-off meeting successfully held.
- 2025/09/01: TUD PhD. student enrolled.
- 2025/03/31: TCD PhD. student 1 enrolled.
## Objectives
Harmonic-AI will
1. Accelerate the development and deployment in the Irish marketplace of competitive energy-related
products, processes and systems: Through HARMONIC-AI project, we would create a community of
policymakers, businesses and consumers and educate and train the stakeholders on various aspects
of EV charger location, consumer preference modelling etc. and make the core data and publications
open access. This would drive more competition and new product development in the ecosystem.
[SEAI Prog. Obj 1]
2. Support solutions that enable technical and other barriers to energy market uptake to be overcome:
HARMONIC-AI will bring together knowledge from power, engineering, consumer business and GIS
fields together to develop solutions for optimal charger location and incentive design, thereby
increasing uptake of EV in Ireland across all population strata. [SEAI Prog. Obj 2]
3. Grow Ireland's national capacity to access, develop and apply international class energy RD&D:
HARMONIC-AI will enable development of a team of multi-disciplinary researchers with international
capability to work in this sector and would also train PhD and Postdoctoral researchers to extend the
leadership position for coming years. [SEAI Prog. Obj 3]
4. Provide guidance and support to policy makers and public bodies through results, outcomes and
learning from supported projects: HARMONIC-AI project proposes to provide an actionable software
tool to policymakers that includes decision making capability and simulate consumer responses and
EV update for different policy interventions. [SEAI Prog. Obj 4]
## Phases
The project is structured into several phases. Following an initial project setup and coordination phase, the first technical phase focuses on the development of lightweight TinyML-based deep learning models for real-time harmonic detection and prediction, including model co-design, quantisation, pruning, and distributed learning strategies. The second phase concentrates on the design and implementation of an intelligent Energy Management System (EMS) capable of optimally scheduling EV charging and managing interactions among renewable energy sources, energy storage systems, and grid constraints. In the final technical phase, the project undertakes system integration and validation, tightly coupling the TinyML harmonic estimators with the EMS to realise a closed-loop smart control framework, which is experimentally validated using hardware-in-the-loop testing. Communication, dissemination, and exploitation activities run throughout the project lifecycle to ensure impact, stakeholder engagement, and knowledge transfer.


Currently, the project researchers are focusing on applying our latest model compression technique to edge ultrafast harmonic estimation models and conducting trials on EV and PV devices.

![HarmonicAIPhases](/assets/img/HarmonicAIPhase.png)

## Publications
[Li, Changhong, Biswajit Basu, and Shreejith Shanker. "LogicSparse: Enabling Engine-Free Unstructured Sparsity for Quantised Deep-learning Accelerators." arXiv preprint arXiv:2511.03079 (2025).](https://arxiv.org/abs/2511.03079)

## Members
![TCD](/assets/img/TCD.png) ![TUD](/assets/img/TUD.png) ![ESB](/assets/img/ESB.jpg)


## Acknowledgments
This work was supported by the Sustainable Energy Authority of Ireland (SEAI) under Grant number 24/RDD/1170.

![SEAI](/assets/img/SEAI.png)