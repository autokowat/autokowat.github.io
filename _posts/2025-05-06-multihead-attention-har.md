---
title: "Multi-Head Attention-Based Framework with Residual Network for Human Action Recognition"
description: |
  An efficient deep learning framework for human action recognition that integrates ResNet-18 for spatial feature extraction, Bi-LSTM for temporal modeling, and multi-head attention mechanisms with motion-based frame selection, achieving 96.60% accuracy on UCF-101 at 222 FPS.
background: /assets/theme/images/activity_tracking.png
author: []
categories: [Publication, Journal Paper, Sensors, Human Action Recognition, Deep Learning]
---

## Multi-Head Attention-Based Framework with Residual Network for Human Action Recognition

Human action recognition (HAR) is essential for understanding and classifying human movements. It is widely used in real-life applications such as human–computer interaction and assistive robotics. However, recognizing patterns across different temporal scales remains challenging. Traditional methods struggle with complex timing patterns, intra-class variability, and inter-class similarities, leading to misclassifications.

In this paper, we propose a deep learning framework for efficient and robust HAR. It integrates residual networks (ResNet-18) for spatial feature extraction and Bi-LSTM for temporal feature extraction. A multi-head attention mechanism enhances the prioritization of crucial motion details. Additionally, we introduce a motion-based frame selection strategy utilizing optical flow to reduce redundancy and enhance efficiency. This ensures accurate, real-time recognition of both simple and complex actions.

We evaluate the framework on the UCF-101 dataset, achieving a **96.60% accuracy**, demonstrating competitive performance against state-of-the-art approaches. Moreover, the framework operates at **222 frames per second (FPS)**, achieving an optimal balance between recognition performance and computational efficiency. The proposed framework was also deployed and tested on a mobile service robot, TIAGo, validating its real-time applicability in real-world scenarios. It effectively models human actions while minimizing frame dependency, making it well-suited for real-time applications.

## Fulltext Access
[https://doi.org/10.3390/s25092930](https://doi.org/10.3390/s25092930)

## Code
[https://github.com/basheeraltawil/HAR-ResNet-BiLSTM-Attention.git](https://github.com/basheeraltawil/HAR-ResNet-BiLSTM-Attention.git)

## Citation (BibTeX)

```bibtex
@article{altawil2025multihead,
  author    = {Basheer Al-Tawil and Magnus Jung and Thorsten Hempel and Ayoub Al-Hamadi},
  title     = {Multi-Head Attention-Based Framework with Residual Network for Human Action Recognition},
  journal   = {Sensors},
  volume    = {25},
  number    = {9},
  pages     = {2930},
  year      = {2025},
  month     = may,
  doi       = {10.3390/s25092930},
  url       = {https://doi.org/10.3390/s25092930}
}
```
