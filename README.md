# Afford-X Project

This repository contains the official implementation of our Afford-X project: A Generalizable and Slim Affordance Reasoning Framework for Task-oriented Manipulation.

[Xiaomeng Zhu]( )<sup>†</sup>, [Yuyang Li]( )<sup>†</sup>, [Leiyao Cui]( ), [Pengfei Li](), [Huan-ang Gao](), [Yixin Zhu](https://yzhu.io/)<sup>✉</sup>, [Hao Zhao](https://sites.google.com/view/fromandto)<sup>✉</sup>

<small><sup>†</sup> Equal contribution, <sup>✉</sup> Corresponding author.</small>

## Introduction
Object affordance reasoning, the ability to infer object functionalities based on physical properties, is fundamental for task-oriented planning and activities in both humans and \ac{ai}. This capability, required for planning and executing daily activities in a task-oriented manner, relies on commonsense knowledge of object physics and functionalities, extending beyond simple object recognition. Current computational models for affordance reasoning from perception lack generalizability, limiting their applicability in novel scenarios. Meanwhile, comprehensive \acp{llm} with emerging reasoning capabilities are challenging to deploy on local devices for task-oriented manipulations. Here, we introduce \affordanceDatasetNamelvis{}, a large-scale dataset comprising 1,496 tasks and 897k images, designed to enhance the generalizability of affordance reasoning from perception. Utilizing this dataset, we develop \affordanceModelName{}, an end-to-end trainable affordance reasoning model that incorporates Verb Attention and Bi-Fusion modules to improve multi-modal understanding. This model achieves up to a 25.5\% performance improvement on unseen categories and tasks, while maintaining a compact 187M parameter size and inferring nearly 50 times faster than the GPT-4V API. Our work demonstrates the potential for efficient, generalizable affordance reasoning models that can be deployed on local devices for task-oriented manipulations. We showcase \affordanceModelName{}'s effectiveness in enabling task-oriented manipulations for robots across various tasks and environments, underscoring its efficiency and broad implications for advancing robotics and \ac{ai} systems in real-world applications.

<p align="center"><img src="media/teaser.png" width="800" /></p>

## Project Components

### [Afford-X Training](https://github.com/ZhuXMMM/Afford-X)
The main training framework containing:
- Model implementation and training code
- Dataset processing and organization
- Pre-trained model weights
- Evaluation scripts

### [Afford-X Manipulation](https://github.com/YuyangLee/Afford-X-Manip)
The manipulation component for robot control and interaction, including:
- Robot control interfaces
- Task planning modules
- Real-world demonstration

## Installation & Usage
Please refer to the README files in each component repository for detailed installation and usage instructions.

## License
This project is released under the MIT License.

## Citation
If you find our code or paper useful, please consider citing:
@misc{zhu2025affordxgeneralizableslimaffordance,
      title={Afford-X: Generalizable and Slim Affordance Reasoning for Task-oriented Manipulation}, 
      author={Xiaomeng Zhu and Yuyang Li and Leiyao Cui and Pengfei Li and Huan-ang Gao and Yixin Zhu and Hao Zhao},
      journal={arXiv preprint arXiv:2503.03556},
      year={2025}
}