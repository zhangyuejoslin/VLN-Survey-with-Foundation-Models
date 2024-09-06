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

🔔 We will update this page frequently~ :tada::tada::tada:

### World Model: Learning and Representing the Visual Environment
A world model helps the VLN agent to understand their surrounding environments, predict how their actions would change the world state, and align their perception and actions with language instructions.
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
[**EnvEdit: Environment Editing for Vision-and-Language Navigation**](https://arxiv.org/abs/2203.15685)| CVPR | 2022| [Github](https://github.com/jialuli-luka/VLN-SIG) |

### Human Model: Interpreting and Communication with Humans
The human model comprehends human-provided natural language instructions per situation to complete navigation tasks. 

|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
[**Spatially-Aware Speaker for Vision-and-Language Navigation Instruction Generation**](https://aclanthology.org/2024.acl-long.734.pdf)| ACL | 2024| [Github](https://github.com/gmuraleekrishna/SAS) |
[**NavHint: Vision and Language Navigation Agent with a Hint Generator**](https://arxiv.org/pdf/2402.02559)| EACL | 2024| [Github](https://github.com/HLR/NavHint) |
[**A New Path: Scaling Vision-and-Language Navigation with Synthetic Instructions and Imitation Learning**](https://arxiv.org/pdf/2210.03112)| CVPR | 2023| [Dataset](https://github.com/google-research-datasets/RxR/tree/main/marky-mT5) |
[**Lana: A Language-Capable Navigator for Instruction Following and Generation**](https://arxiv.org/abs/2303.08409)| CVPR | 2023| [Github](https://github.com/wxh1996/LANA-VLN) |
[**VLN-Trans: Translator for the Vision and Language Navigation Agent**](https://arxiv.org/pdf/2302.09230)| ACL | 2023| [Github](https://github.com/HLR/VLN-trans) |
[**Less is More: Generating Grounded Navigation Instructions from Landmarks**](https://arxiv.org/pdf/2111.12872)| CVPR | 2022| [Dataset](https://github.com/google-research-datasets/RxR/tree/main/marky-mT5) |
[**Visual-Language Navigation Pretraining via Prompt-based Environmental Self-exploration**](https://arxiv.org/pdf/2203.04006)| ACL | 2022| [Github](https://github.com/liangcici/Probes-VLN) |
[**Towards Learning a Generic Agent for Vision-and-Language Navigation via Pre-training**](https://arxiv.org/pdf/2004.14973)| CVPR | 2020| [Github](https://github.com/weituo12321/PREVALENT) |
[**Improving Vision-and-Language Navigation with Image-Text Pairs from the Web**](https://arxiv.org/pdf/2002.10638)| ECCV | 2020| [Github](https://github.com/arjunmajum/vln-bert) |

### VLN Agent: Learning an Embodied Agent for Reasoning and Planning

|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
[**Actional Atomic-Concept Learning for Demystifying Vision-Language Navigation**](https://arxiv.org/pdf/2302.06072)| AAAI | 2023| - |
[**HOP+: History-Enhanced and Order-Aware Pre-Training for Vision-and-Language Navigation**](https://ieeexplore.ieee.org/document/10006384)| TPAMI | 2023 | - |
[**HOP: History-and-Order Aware Pre-training for Vision-and-Language Navigation**](https://ieeexplore.ieee.org/document/9880046)| CVPR | 2022| [Github](https://github.com/YanyuanQiao/HOP-VLN)|
[**LOViS: Learning Orientation and Visual Signals for Vision and Language Navigation**](https://aclanthology.org/2022.coling-1.505.pdf)| COLING | 2022| [Github](https://github.com/HLR/LOViS) |
[**Scene-Intuitive Agent for Remote Embodied Visual Grounding**](https://arxiv.org/pdf/2103.12944)| CVPR | 2021| - |


