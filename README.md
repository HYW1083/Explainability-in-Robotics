# Explainability-in-Robotics
Explainable AI for Robotics in the Era of Foundation Models: A Survey

Explainability is a critical aspect of AI-driven robotic systems, ensuring transparency, trust, and interpretability in decision-making processes. This repository provides a survey of literature related to explainable AI (XAI) in robotics.

## Contents
- [Survey](#survey)
  - [Survey Papers](#survey-papers)
- [Perception](#perception)
  - [Vision](#vision)
  - [Logs](#logs)
  - [Audio](#audio)
  - [Others](#Others)
- [Planning](#planning)
  - [Decision Making](#decision-making)
  - [Knowledge-Based Reasoning](#knowledge-based-reasoning)
  - [Chain of Thought](#chain-of-thought)
- [Action](#action)
## Survey

### Suvey papers
| Date | Venue | Paper | Institution |
| ---- | ---- | ---- | ---- |
|2022 | Advanced Robotics| [Explainable autonomous robots: a survey and perspective](https://doi.org/10.1080/01691864.2022.2029720) | University of Electro-Communications |
|2023 | ACM Computing Surveys | [Explainable Goal-driven Agents and Robots - A Comprehensive Review](https://dl.acm.org/doi/pdf/10.1145/3564240)|University of Malaya |
|2024 | ACM Computing Surveys | [Who’s in Charge Here? A Survey on Trustworthy AI in Variable Autonomy Robotic Systems](https://dl.acm.org/doi/pdf/10.1145/3645090) | Umeå University |
|2024 |[IEEE TAC](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=5165369) |[Explainable AI for Audio and Visual Affective Computing: A Scoping Review](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10766406) |Bielefeld University |
|2025 | Arxiv |[Explainable artificial intelligence (XAI): from inherent explainability to large language models](https://arxiv.org/pdf/2501.09967)|Cape Coast Technical University|
|2025 | Arxiv | [Explainability for Vision Foundation Models: A Survey](https://arxiv.org/pdf/2501.12203)| Institut Polytechnique de Paris |


### Perception

#### Vision

| Date | Venue  | Paper | Project | Institution | 
| ---- | ---- | ---- | ---- | ---- |
|2023  | CVPR |  [CoWs on PASTURE: Baselines and Benchmarks for Language-Driven Zero-Shot Object Navigation](https://openaccess.thecvf.com/content/CVPR2023/papers/Gadre_CoWs_on_Pasture_Baselines_and_Benchmarks_for_Language-Driven_Zero-Shot_Object_CVPR_2023_paper.pdf) |[CoW](https://cow.cs.columbia.edu/) | Columbia University |
|2024 | IROS |  [VLPG-Nav: Object Navigation Using Visual Language Pose Graph and  Object Localization Probability Maps](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10802008) | VLPG-Nav | Amazon |
|2025 | [EAAI](https://www.sciencedirect.com/journal/engineering-applications-of-artificial-intelligence) | [Integrating Belief-Desire-Intention agents with large language models for reliable human–robot interaction and explainable Artificial Intelligence](https://doi.org/10.1016/j.engappai.2024.109771) |  | BOKU University |
|2025 | Arxiv |[Tell me why:  Visual foundation models as self-explainable classifiers](https://arxiv.org/abs/2502.19577) |[ProtoFM](https://github.com/hturbe/proto-fm)| University of Geneva |

#### Logs
| Date | Venue  | Paper | Project | Institution | 
| ---- | ---- | ---- | ---- | ---- |
|2023 |[HAIS](https://link.springer.com/conference/hais) | [Using Large Language Models for Interpreting Autonomous Robots Behaviors](https://arxiv.org/pdf/2304.14844)| |University of León |
|2024 |Arxiv|[Explaining Autonomy: Enhancing Human-Robot Interaction through Explanation Generation with Large Language Models](https://arxiv.org/pdf/2402.04206) | | University of León |
|2024 |Arxiv|[Enhancing Robot Explanation Capabilities through Vision-Language Models: a Preliminary Study by Interpreting Visual Inputs for Improved Human-Robot Interaction](https://arxiv.org/pdf/2404.09705) | | University of León |
|2024 |Arxiv|[Enhancing Trust in Autonomous Agents: An Architecture for Accountability and Explainability through Blockchain and Large Language Models](https://arxiv.org/pdf/2403.09567)| | University of León|

#### Audio

| Date | Venue  | Paper | Project | Institution | 
| ---- | ---- | ---- | ---- | ---- |
|2023 |[ROMAN](https://ieeexplore.ieee.org/xpl/conhome/10309296/proceeding)  | [Designing Visual and Auditory Attention-Driven Movements of a Tabletop Robot](https://ieeexplore.ieee.org/iel7/10309296/10309265/10309568.pdf) | |Honda Research |
|2023 |[ISER](https://link.springer.com/chapter/10.1007/978-3-031-63596-0_10) |[Audio Visual Language Maps for Robot Navigation](https://arxiv.org/pdf/2303.07522)  | [AVLMaps](https://avlmaps.github.io/) |University of Freiburg |
|2024 |AIiH |[Interpreting Pretrained Speech Models for Automatic Speech Assessment of Voice Disorders](https://arxiv.org/pdf/2407.00531)| |University of Wales Trinty Saint David| 
|2025 |CVIU |[A multi-modal explainability approach for human-aware robots in multi-party conversation](https://doi.org/10.1016/j.cviu.2025.104304) | [Code](https://zenodo.org/records/14833239) | Italian Institute of Technology |

#### Others

| Date | Venue  | Paper | Project | Institution | 
| ---- | ---- | ---- | ---- | ---- |
|2022 | CoRL | [Safety-Enhanced Autonomous Driving Using Interpretable Sensor Fusion Transformer](https://proceedings.mlr.press/v205/shao23a/shao23a.pdf)| [InterFuser](https://github.com/opendilab/InterFuser)|SenseTime Research|
|2025  |Applied Sciences |[Explainable AI-Enhanced Human Activity Recognition for Human–Robot Collaboration in Agriculture](http://dx.doi.org/10.3390/app15020650) | |CERTH|
|2025 | Information Fusion  | [SaliencyI2PLoc: Saliency-guided image–point cloud localization using contrastive learning](https://doi.org/10.1016/j.inffus.2025.103015) | [SaliencyI2PLoc](https://whu-lyh.github.io/SaliencyI2PLoc/) |Wuhan University|

### Task Planning
(log-based explanation and model-based explanation)
#### Decision making

| Date | Venue  | Paper | Project | Institution | 
| ---- | ---- | ---- | ---- | ---- |
|2021 |ACM HRI |[Explainable AI for Robot Failures: Generating Explanations that Improve User Assistance in Fault Recovery](https://dl.acm.org/doi/pdf/10.1145/3434073.3444657) | | Georgia Institute of Technology|
|2022 |RO-MAN |[Explain yourself! Effects of Explanations in Human-Robot Interaction](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9900558)| |Universitat Hamburg|
|2024 | RLC  | [Towards Interpretable Foundation Models of Robot Behavior: A Task Specific Policy Generation Approach](https://arxiv.org/pdf/2407.08065)| DPP | Tufts University |
|2024  | Arxiv| [Social-LLaVA: Enhancing Robot Navigation through Human-Language  Reasoning in Social Spaces](https://arxiv.org/pdf/2501.09024) |[Social-LLaVA](https://cs.gmu.edu/~xiao/Research/SNEI/)  | George Mason University  |
|2024 | Arxiv |[Trustworthy Conceptual Explanations for Neural Networks in Robot Decision-Making](https://arxiv.org/pdf/2409.10733)|[BaTCAVe](https://github.com/aditya-taparia/BaTCAVe)| Arizona State University |
|2024 |[Front.Robot.AI](https://www.frontiersin.org/journals/robotics-and-ai) |[ExTraCT – Explainable trajectory corrections for language-based human-robot interaction using textual feature descriptions](https://www.frontiersin.org/journals/robotics-and-ai/articles/10.3389/frobt.2024.1345693/full)|ExTraCT|Nanyang Technological University|
|2024 |NeurIPS|[RoboMamba: Efficient Vision-Language-Action Model for Robotic Reasoning and Manipulation](https://arxiv.org/pdf/2406.04339)|[RoboMamba](https://sites.google.com/view/robomamba-web)|BAAI|
|2025 | ICRA | [Language to Map: Topological map generation from natural language path instructions](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10611377)|Language to Map |Toyota|
|2025 | Arxiv|[ChatVLA: Unified Multimodal Understanding and Robot Control with Vision-Language-Action Model](https://arxiv.org/pdf/2502.14420) |[ChatVLA](https://chatvla.github.io/) |Midea Group |

#### Kownleged-based reasoning
| Date | Venue  | Paper | Project | Institution | 
| ---- | ---- | ---- | ---- | ---- |
| 2024 | [EAAI](https://doi.org/10.1201/9781003355281) | [Integrated Knowledge-Based Reasoning and Data-Driven Learning for Explainable Agency in Robotics](https://homepages.inf.ed.ac.uk/msridhar/Papers/bookchap23_explAgencyRobotics.pdf)| | University of Birmingham |

#### Chain of Thought
| Date | Venue  | Paper | Project | Institution | 
| ---- | ---- | ---- | ---- | ---- |

### Action Generation
| Date | Venue  | Paper | Project | Institution | 
| ---- | ---- | ---- | ---- | ---- |












