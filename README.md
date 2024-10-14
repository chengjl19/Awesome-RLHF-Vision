# Awesome-RLHF-Vision

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
![visitor badge](https://visitor-badge.lithub.cc/badge?page_id=chengjl19.Awesome-RLHF-Vision&left_text=Visitors)
![GitHub stars](https://img.shields.io/github/stars/chengjl19/Awesome-RLHF-Vision?color=yellow)
![GitHub forks](https://img.shields.io/github/forks/chengjl19/Awesome-RLHF-Vision?color=9cf)
[![GitHub license](https://img.shields.io/github/license/chengjl19/Awesome-RLHF-Vision)](https://github.com/chengjl19/Awesome-RLHF-Vision/blob/main/LICENSE)

## Introduction

Welcome to the **Awesome-RLHF-Vision** repository! This is a curated collection of research papers focusing on **Reinforcement Learning with Human Feedback** (RLHF) as applied to **vision models**. Our goal is to create a comprehensive resource that is continuously updated to track the latest advancements in this exciting field.

---
⭐ If you find this repository useful or interesting, please consider giving it a star to show your support! ⭐
---

## Table of Contents

1. [Introduction](#introduction)
2. [Research Papers](#research-papers)
    - [Papers](#papers)
        - [2024](#2024)
        - [2023](#2023)
    - [Datasets](#datasets)
3. [Contributing](#contributing)
4. [License](#license)
5. [Acknowledgements](#acknowledgements)
6. [Contact](#contact)

## Research Papers

Here you can find a list of research papers categorized by topics related to RLHF for vision models. 

```
format:
- [title](paper link) [links]
  - author1, author2, and author3...
  - publisher
  - keyword
  - summary
  - code
  - experiment environments and datasets
```

### Papers

#### 2024

#### 2023

- [RLHF-V: Towards Trustworthy MLLMs via Behavior Alignment from Fine-grained Correctional Human Feedback](https://arxiv.org/abs/2312.00849)
  - Tianyu Yu, Yuan Yao, Haoye Zhang, Taiwen He, Yifeng Han, Ganqu Cui, Jinyi Hu, Zhiyuan Liu, Hai-Tao Zheng, Maosong Sun, Tat-Seng Chua
  - CVPR 2024
  - Keyword: Multimodal Understanding, Hallucination, Dense Direct Preference Optimization, Human-annotated, MiniCPM
  - Code: [Official](https://github.com/RLHF-V/RLHF-V)


- [Diffusion Model Alignment Using Direct Preference Optimization](https://arxiv.org/abs/2311.12908)
  - Bram Wallace, Meihua Dang, Rafael Rafailov, Linqi Zhou, Aaron Lou, Senthil Purushwalkam, Stefano Ermon, Caiming Xiong, Shafiq Joty, Nikhil Naik
  - Keyword: Image Generation, Image-to-Image Editing, DPO, SDXL-1.0
  - Code: [Official](https://github.com/SalesforceAIResearch/DiffusionDPO)


- [Pick-a-Pic: An Open Dataset of User Preferences for Text-to-Image Generation](https://arxiv.org/abs/2305.01569)
  - Yuval Kirstain, Adam Polyak, Uriel Singer, Shahbuland Matiana, Joe Penna, Omer Levy
  - NeurIPS 2023
  - Keyword: Image Generation, Reward Model, Human Preference Dataset
  - Code: [Official](https://github.com/yuvalkirstain/PickScore)

- [ImageReward: Learning and Evaluating Human Preferences for Text-to-Image Generation](https://arxiv.org/abs/2304.05977)
  - Jiazheng Xu, Xiao Liu, Yuchen Wu, Yuxuan Tong, Qinkai Li, Ming Ding, Jie Tang, Yuxiao Dong
  - NeurIPS 2023
  - Keyword: Image Generation, Reward Model, Reward Feedback Learning
  - Code: [Official](https://github.com/THUDM/ImageReward)

- [Aligning text-to-image models using human feedback](https://arxiv.org/abs/2302.12192)
  - Kimin Lee, Hao Liu, Moonkyung Ryu, Olivia Watkins, Yuqing Du, Craig Boutilier, Pieter Abbeel, Mohammad Ghavamzadeh, Shixiang Shane Gu
  - NeurIPS 2023
  - Keyword: Image Generation, Reward Model, Reward-weighted Learning


- [Human Preference Score: Better Aligning Text-to-Image Models with Human Preference](https://arxiv.org/abs/2303.14420)
  - Xiaoshi Wu, Keqiang Sun, Feng Zhu, Rui Zhao, Hongsheng Li
  - ICCV 2023
  - Keyword: Image Generation, Reward Model (human preference classifier), Preference Tuning
  - Code: [Official](https://github.com/tgxs002/align_sd)

- [Rich Human Feedback for Text-to-Image Generation](https://arxiv.org/abs/2312.10240)
  - Youwei Liang, Junfeng He, Gang Li, Peizhao Li, Arseniy Klimovskiy, Nicholas Carolan, Jiao Sun, Jordi Pont-Tuset, Sarah Young, Feng Yang, Junjie Ke, Krishnamurthy Dj Dvijotham, Katie Collins, Yiwen Luo, Yang Li, Kai J Kohlhoff, Deepak Ramachandran, Vidhya Navalpakkam
  - CVPR 2024 Best Paper
  - Keyword: Image Generation, High-resolution, Reward/Critic Model, Fine-grained Feedback Signals, RFT
  - Code: [Official](https://github.com/tgxs002/align_sd)

### Datasets

- [RLHF-V-Dataset](https://huggingface.co/datasets/openbmb/RLHF-V-Dataset)
  - OpenBMB
  - Keyword: Human Preference, Rankings, Trustworthiness
  - Task: Diverse multimodal understanding tasks

- [RLAIF-V-Dataset](https://huggingface.co/datasets/openbmb/RLAIF-V-Dataset)
  - OpenBMB
  - Keyword: AI Preference, Rankings, Trustworthiness
  - Task: Diverse multimodal understanding tasks

- [Picka-Pic-v1](https://huggingface.co/datasets/yuvalkirstain/pickapic_v1)
    - Yuval Kirstain and Adam Polyak and Uriel Singer and Shahbuland Matiana and Joe Penna and Omer Levy
    - Keyword: Human Preference, Rankings
    - Task: Image Generation

- [Picka-Pic-v2](https://huggingface.co/datasets/yuvalkirstain/pickapic_v2)
    - Yuval Kirstain and Adam Polyak and Uriel Singer and Shahbuland Matiana and Joe Penna and Omer Levy
    - Keyword: Human Preference, Rankings
    - Task: Image Generation


- [ImageRewardDB](https://huggingface.co/datasets/THUDM/ImageRewardDB)
    - THUDM
    - Keyword: Human Preference, Rankings
    - Task: Image Generation

- [Simulacra Aesthetic Captions](https://github.com/JD-P/simulacra-aesthetic-captions)
    - John David Pressman and Katherine Crowson and Simulacra Captions Contributors
    - Keyword: Human Preference, Ratings
    - Task: Image Generation

- [HPS](https://mycuhk-my.sharepoint.com/:u:/g/personal/1155172150_link_cuhk_edu_hk/ESCl7RD3cE9FsitV0P2F8DABC1zRJxbCMI-AXei2Nwx2vA?e=ILRanj)
    - Xiaoshi Wu and Keqiang Sun and Feng Zhu and Rui Zhao and Hongsheng Li
    - Keyword: Human Preference, Ratings
    - Task: Image Generation

- [RichHF-18k](https://github.com/google-research-datasets/richhf-18k)
    - Google Research
    - Keyword: Human Preference, Ratings, Human-labeled Heatmaps (e.g., artifact regions of distorted pixels) and Misalignment Tokens in Prompts
    - Task: Image Generation

<br>

> *Note:* This list is continually updated. Make sure to check back regularly for the most recent papers.

## Contributing

We welcome contributions from the community! If you have a paper or resource you'd like to add, feel free to submit a pull request or open an issue. Please follow our [contribution guidelines](contribution_guidelines.md) for details.

---

## License

This repository is licensed under the MIT License. See the [LICENSE](https://github.com/chengjl19/Awesome-RLHF-Vision/blob/main/LICENSE) file for more information.

---

## Acknowledgements

We would like to thank the contributors and researchers whose efforts have made this compilation possible.

## Contact

For any questions or suggestions, feel free to open an issue or contact us directly (jialechengchn@gmail.com). We appreciate your feedback!

---

Thank you for visiting **Awesome-RLHF-Vision**! Happy reading and researching!