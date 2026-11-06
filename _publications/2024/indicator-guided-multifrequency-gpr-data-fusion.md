---
title: "Indicator-Guided Multifrequency GPR Data Fusion with Transformer"
date: 2024-7-24
selected: true
links:
  Paper:
    url: https://ieeexplore.ieee.org/abstract/document/10608180
    target: _blank
pub: IEEE Transactions on Geoscience and Remote Sensing
abstract: >-
  Multifrequency ground penetrating radar (GPR) data fusion integrates complementary information from multiple single central frequency measurements into a composite radargram, broadening the spectral bandwidth of signals and improving interpretation efficiency and accuracy. Here, we develop an indicator-guided multifrequency GPR data fusion algorithm with the transformer network. Instead of generating the fusion result directly, we design the fusion network to integrate the fusion process of combining original multifrequency GPR data with the main idea of learning to understand the difference between different single central frequency data and then producing fusion weights, ultimately resulting in the fused GPR data. The indicator we used, which is the 1-D Laplacian operator gradient representing the importance of each central frequency data at different time windows, guides the network to preserve as much high-resolution information as possible in the overlapping area. The results of synthetic, experimental, and field data indicate that, compared with the recently developed long short-term memory network (LSTM)-based fusion algorithm, the proposed algorithm shows high efficiency and provides better fusion results that retain more high-resolution information from high-frequency data without losing deep signals from low-frequency data. Moreover, it presents a good generalization capability for datasets with a similar acquisition situation. Therefore, it provides an effective real-time multifrequency GPR fusion solution, especially for cases where a large amount of multifrequency GPR data measured under similar circumstances needs to be fused.
authors:
  - Shufan Hu
  - Huilin Zhou
  - Yonghui Zhao;
  - Wei Cai
  - Kunwei Feng
---
