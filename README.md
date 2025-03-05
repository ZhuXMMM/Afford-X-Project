# Afford-X Project

This repository contains the official implementation of our Afford-X project: A Generalizable and Slim Affordance Reasoning Framework for Task-oriented Manipulation.

[Xiaomeng Zhu]( )<sup>†</sup>, [Yuyang Li]( )<sup>†</sup>, [Leiyao Cui]( ), [Pengfei Li](), [Huan-ang Gao](), [Yixin Zhu](https://yzhu.io/)<sup>✉</sup>, [Hao Zhao](https://sites.google.com/view/fromandto)<sup>✉</sup>

<small><sup>†</sup> Equal contribution, <sup>✉</sup> Corresponding author.</small>

## Introduction
Object affordance reasoning, the ability to infer object functionalities based on physical properties, is fundamental for task-oriented planning and activities in both humans and AI. This capability, required for planning and executing daily activities in a task-oriented manner, relies on commonsense knowledge of object physics and functionalities, extending beyond simple object recognition. Current computational models for affordance reasoning from perception lack generalizability, limiting their applicability in novel scenarios.

<p align="center"><img src="Afford-X/media/teaser.png" width="600" /></p>

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