# 👏 Survey of Vision-and-Language Navigation 
This is the official repository of "**[Vision-and-Language Navigation Today and Tomorrow: A Survey in the Era of Foundation Models](https://arxiv.org/pdf/2407.07035)**", a comprehensive survey 
of recent progress in VLN with foundation models.

## Introduction
Vision-and-Language Navigation (VLN) has gained increasing attention over recent years and many approaches have emerged to advance their development. The remarkable achievements of foundation models have shaped the challenges and proposed methods for VLN research. In this survey, we provide a top-down review that adopts a principled framework for embodied planning and reasoning and emphasizes the current methods and future opportunities leveraging foundation models to address VLN challenges. We hope our in-depth discussions could provide valuable resources and insights: on the one hand, to document the progress and explore opportunities and potential roles for foundation models in this field, and on the other, to organize different challenges and solutions in VLN to foundation model researchers.

## Citation
If you find our work useful in your research, please consider citing:

    @article{zhang2024vision,
      title={Vision-and-Language Navigation Today and Tomorrow: A Survey in the Era of Foundation Models},
      author={Zhang, Yue and Ma, Ziqiao and Li, Jialu and Qiao, Yanyuan and Wang, Zun and Chai, Joyce and Wu, Qi and Bansal, Mohit and Kordjamshidi, Parisa},
      journal={arXiv preprint arXiv:2407.07035},
      year={2024}
    }

🔔 We will update this page frequently. If you believe additional work should be included, please do not hesitate to email us (zhan1624@msu.edu) or raise an issue. Your suggestions and comments are invaluable to ensuring the completeness of our resources.

## Content
---
- [Relevant Surveys](#relevant-surveys)
- [World Model](#word-modal)
- [Human Model](#human-modal)
- [VLN Agent](#vln-agent-learning-an-embodied-agent-for-reasoning-and-planning)


---
## Relevant Surveys
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
[**Vision-and-Language Navigation: A Survey of Tasks, Methods, and Future Directions**](https://arxiv.org/abs/2203.12667)| ACL | 2022| [Github](https://github.com/eric-ai-lab/awesome-vision-language-navigation) |
[**Vision-Language Navigation: A Survey and Taxonomy**](https://arxiv.org/abs/2108.11544)| - | 2021| - |
---
## World Model
A world model helps the VLN agent to understand their surrounding environments, predict how their actions would change the world state, and align their perception and actions with language instructions.
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
[**VLN-Video: Utilizing Driving Videos for Outdoor Vision-and-Language Navigation**](https://arxiv.org/abs/2402.03561)| AAAI | 2024| - |
[**Vision Language Navigation with Knowledge-driven Environmental Dreamer**](https://www.ijcai.org/proceedings/2023/0204.pdf)| IJCAI | 2023| - |
[**Frequency-enhanced Data Augmentation for Vision-and-Language Navigation**](https://openreview.net/pdf?id=eKFrXWb0sT)| NeurIPS | 2023| [Github](https://github.com/hekj/FDA?tab=readme-ov-file) |
[**Frequency-Enhanced Data Augmentation for Vision-and-Language Navigation**](https://proceedings.neurips.cc/paper_files/paper/2023/file/0d9e08f247ca7fbbfd5e50b7ff9cf357-Paper-Conference.pdf)| NeurIPS | 2023| [Github](https://github.com/hekj/FDA) |
[**Panogen: Text-conditioned panoramic environment generation for vision-and-language navigation**](https://arxiv.org/abs/2305.19195)| NeurIPS | 2023| [Github](https://github.com/jialuli-luka/PanoGen) |
[**Simple and Effective Synthesis of Indoor 3D Scenes**](https://arxiv.org/pdf/2204.02960)| AAAI | 2023| [Github](https://github.com/google-research/se3ds) |
[**Learning vision-and-language navigation from youtube videos**](https://arxiv.org/abs/2307.11984)| ICCV | 2023| [Github](https://github.com/JeremyLinky/YouTube-VLN) |
[**Scaling Data Generation in Vision-and-Language Navigation**](https://arxiv.org/abs/2307.15644)| ICCV | 2023| [Github](https://github.com/wz0919/ScaleVLN/tree/main?tab=readme-ov-file) |
[**A New Path: Scaling Vision-and-Language Navigation with Synthetic Instructions and Imitation Learning**](https://arxiv.org/abs/2210.03112)| CVPR | 2023| [Github](https://github.com/google-research-datasets/RxR/tree/main/marky-mT5)  |
[**EnvEdit: Environment Editing for Vision-and-Language Navigation**](https://arxiv.org/abs/2203.15685)| CVPR | 2022| [Github](https://github.com/jialuli-luka/VLN-SIG)|
[**History Aware Multimodal Transformer for Vision-and-Language Navigation**](https://arxiv.org/abs/2110.13309)| NeurIPS | 2021| [Github](https://cshizhe.github.io/projects/vln_hamt.html) |
[**Pathdreamer: A World Model for Indoor Navigation**](https://arxiv.org/abs/2105.08756)| ICCV | 2021| - |
[**Airbert: In-domain Pretraining for Vision-and-Language Navigation**](https://arxiv.org/abs/2108.09105)| ICCV | 2021| [Github](https://airbert-vln.github.io/) |
[**Vision-Language Navigation with Random Environmental Mixup**](https://arxiv.org/abs/2106.07876)| ICCV | 2021| [Github](https://github.com/LCFractal/VLNREM) |

## Human Model: Interpreting and Communication with Humans
The human model comprehends human-provided natural language instructions per situation to complete navigation tasks. 

|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
[**Spatially-Aware Speaker for Vision-and-Language Navigation Instruction Generation**](https://aclanthology.org/2024.acl-long.734.pdf)| ACL | 2024| [Github](https://github.com/gmuraleekrishna/SAS) |
[**Correctable Landmark Discovery via Large Models for Vision-Language Navigation**](https://arxiv.org/abs/2405.18721)| TPAMI | 2024| [Github](https://github.com/expectorlin/CONSOLE) |
[**NavHint: Vision and Language Navigation Agent with a Hint Generator**](https://arxiv.org/pdf/2402.02559)| EACL | 2024| [Github](https://github.com/HLR/NavHint) |
[**A New Path: Scaling Vision-and-Language Navigation with Synthetic Instructions and Imitation Learning**](https://arxiv.org/pdf/2210.03112)| CVPR | 2023| [Dataset](https://github.com/google-research-datasets/RxR/tree/main/marky-mT5) |
[**Learning vision-and-language navigation from youtube videos**](https://arxiv.org/abs/2307.11984)| ICCV | 2023| [Github](https://github.com/JeremyLinky/YouTube-VLN) |
[**Lana: A Language-Capable Navigator for Instruction Following and Generation**](https://arxiv.org/abs/2303.08409)| CVPR | 2023| [Github](https://github.com/wxh1996/LANA-VLN) |
[**VLN-Trans: Translator for the Vision and Language Navigation Agent**](https://arxiv.org/pdf/2302.09230)| ACL | 2023| [Github](https://github.com/HLR/VLN-trans) |
[**Visual-Language Navigation Pretraining via Prompt-based Environmental Self-exploration**](https://arxiv.org/pdf/2203.04006)| ACL | 2022| [Github](https://github.com/liangcici/Probes-VLN) |
[**Less is More: Generating Grounded Navigation Instructions from Landmarks**](https://arxiv.org/pdf/2004.14973)| CVPR | 2022| [Github](https://github.com/google-research-datasets/RxR/tree/main/marky-mT5) |
[**Do As I Can, Not As I Say:Grounding Language in Robotic Affordances**](https://say-can.github.io/assets/palm_saycan.pdf)| - | -| [Github](https://say-can.github.io/) |
[**Explicit Object Relation Alignment for Vision and Language Navigation**](https://aclanthology.org/2022.acl-srw.24.pdf)| ACL-SRW | 2022| [Github](https://github.com/HLR/Object-Grounding-for-VLN) |
[**Towards Navigation by Reasoning over Spatial Configurations**](https://arxiv.org/abs/2105.06839)| SpLU | 2021| [Github](https://github.com/zhangyuejoslin/SpC-NAV) |

## VLN Agent: Learning an Embodied Agent for Reasoning and Planning

|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
[**Actional Atomic-Concept Learning for Demystifying Vision-Language Navigation**](https://arxiv.org/pdf/2302.06072)| AAAI | 2023| - |
[**Grounded Entity-Landmark Adaptive Pre-training for Vision-and-Language Navigation**](https://arxiv.org/abs/2308.12587)| ICCV | 2023| [Github](https://arxiv.org/pdf/2305.14268)  |
[**Adaptive Zone-aware Hierarchical Planner for Vision-Language Navigation**](https://openaccess.thecvf.com/content/CVPR2023/papers/Gao_Adaptive_Zone-Aware_Hierarchical_Planner_for_Vision-Language_Navigation_CVPR_2023_paper.pdf)| ICCV | 2023| [Github](https://github.com/chengaopro/AZHP)  |
[**Masked Path Modeling for Vision-and-Language Navigation**](https://arxiv.org/pdf/2305.14268)| EMNLP | 2023| - |
[**Bird's-Eye-View Scene Graph for Vision-Language Navigation**](https://arxiv.org/abs/2308.04758)| ICCV | 2023| - |
[**Improving Vision-and-Language Navigation by Generating Future-View Image Semantics**](https://arxiv.org/pdf/2304.04907)| CVPR | 2023| [Github](https://github.com/jialuli-luka/VLN-SIG) |
[**HOP+: History-Enhanced and Order-Aware Pre-Training for Vision-and-Language Navigation**](https://ieeexplore.ieee.org/document/10006384)| TPAMI | 2023 | - |
[**HOP: History-and-Order Aware Pre-training for Vision-and-Language Navigation**](https://ieeexplore.ieee.org/document/9880046)| CVPR | 2022| [Github](https://github.com/YanyuanQiao/HOP-VLN)|
[**LOViS: Learning Orientation and Visual Signals for Vision and Language Navigation**](https://aclanthology.org/2022.coling-1.505.pdf)| COLING | 2022| [Github](https://github.com/HLR/LOViS) |
[**Scene-Intuitive Agent for Remote Embodied Visual Grounding**](https://arxiv.org/pdf/2103.12944)| CVPR | 2021| - |

### LLM-based VLN Agent


#### Zero-shot
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
[**Discuss Before Moving: Visual Language Navigation via Multi-expert Discussions**](https://ieeexplore.ieee.org/abstract/document/10611565) | ICRA | 2024 | [Github](https://github.com/LYX0501/DiscussNav) |
[**MapGPT: Map-Guided Prompting with Adaptive Path Planning for Vision-and-Language Navigation**](https://arxiv.org/abs/2401.07314) | ACL | 2024 | [Github](https://chen-judge.github.io/MapGPT/)
[**MC-GPT: Empowering Vision-and-LanguageNavigation with Memory Map and Reasoning Chains**](https://arxiv.org/pdf/2405.10620) | - | 2024 | - |
[**InstructNav: Zero-shot System for Generic Instruction Navigation in Unexplored Environment**](https://arxiv.org/pdf/2406.04882) | - | 2024 | [Github](https://github.com/LYX0501/InstructNav)
[**NavGPT: Explicit Reasoning in Vision-and-Language Navigation with Large Language Models**](https://arxiv.org/abs/2305.16986) | CVPR | 2023 | [Github](https://github.com/GengzeZhou/NavGPT) |


#### Fine-tuning
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
[**LangNav: Language as a Perceptual Representation for Navigation**](https://aclanthology.org/2024.findings-naacl.60.pdf) | NACCL Findings | 2024 | [Github](https://github.com/pbw-Berwin/LangNav)
[**NavCoT: Boosting LLM-Based Vision-and-Language Navigation via Learning Disentangled Reasoning**](https://arxiv.org/abs/2403.07376)   | CVPR | 2024 | [Github](https://github.com/expectorlin/NavCoT)
[**Towards Learning a Generalist Model for Embodied Navigation**](https://arxiv.org/abs/2312.02010) | CVPR | 2024 | [Github](https://github.com/LaVi-Lab/NaviLLM)
[**NavGPT-2: Unleashing Navigational Reasoning Capability for Large Vision-Language Models**](https://www.arxiv.org/abs/2407.12366) | ECCV | 2024 | [Github](https://github.com/GengzeZhou/NavGPT-2) |


