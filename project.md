# Research Projects
## Content
1. [Tracking](#tracking)
2. [Human Pose Estimation](#human-pose-estimation)
3. [Radar Object Detection](#radar-object-detection)
4. [Domain Adaptation](#domain-adaptation)
5. [Generation for Perception](#generation-for-perception)
6. [LLM](#llm)
7. [Continual Learning](#continual-learning)
8. [Fish Pose Estimation and Length Measurement](#fish-pose-estimation)

## Tracking

- AICity Challenge
  - IEEE/CVF CVPR AICity Challenge 2023
    - Winner of Track 1: Multi-Camera People Tracking
  - IEEE/CVF CVPR AICity Challenge 2019
    - Winner of Track 1: City-Scale Multi-Camera Vehicle Tracking
    - Runner-up of Track 2: City-Scale Multi-Camera Vehicle Reidentification
    - Runner-up of Track 3: Traffic Anomaly Detection
  - IEEE/CVF CVPR AICity Challenge 2018
    - Winner of Track 1: Traffic Flow Analysis
    - Winner of Track 3: Multi-sensor Vehicle Detection and Reidentification

- BMTT (Benchmarking Multi-Target Tracking) Challenge 
  - IEEE/CVF ICCV BMTT Challenge 2021
    - Winner of Video Track: KITTI-STEP
    - Winner of Vdeo Track: MOTChallenge-STEP
  - IEEE/CVF CVPR BMTT Challenge 2020
    - Winner of Track 3: MOTChallenge+KITTI (Tracking)
    - Runner-up of Track 2: KITTI-MOTS (Tracking and Segmentation)

- IEEE/CVF WACV MaCVi Challenge 2024
  - Winner of Track: UAV-based Multi-Object Tracking with Reidentification
  - Winner of Track: USV-based Multi-Object Tracking


### Single-Camera Multi-Object Tracking

### Cross-Camera Multi-Object Tracking

### USV Multi-Object Tracking

## Human Pose Estimation

<p> 
    <strong>
    Global Adaptation meets Local Generalization: Unsupervised Domain Adaptation for 3D Human Pose Estimation
    </strong>
    <br>
    Wenhao Chai, Zhongyu Jiang, Jenq-Neng Hwang, Gaoang Wang
    <br>
    <font color="#E89B00">
    <em>International Conference on Computer Vision (ICCV), 2023</em>
    </font>
    <br>
    <a href="https://arxiv.org/abs/2303.16456">[Paper]</a>
    <a href="https://github.com/rese1f/PoseDA">[Code]</a>
    <img alt="NPM" src="https://img.shields.io/github/stars/rese1f/PoseDA?style=social">
    <br>
    <font color="grey" size="2">
    A simple yet effective framework of unsupervised domain adaptation for 3D human pose estimation.
    </font>
</p>

<p> 
    <strong>
    MPM: A Unified 2D-3D Human Pose Representation via Masked Pose Modeling
    </strong>
    <br>
    Zhenyu Zhang*, Wenhao Chai*, Zhongyu Jiang, Tian Ye, Mingli Song, Jenq-Neng Hwang, Gaoang Wang
    <br>
    <em>arXiv Preprint.</em>
    <br>
    <a href="https://arxiv.org/abs/2306.17201">[Paper]</a>
    <a href="https://github.com/vvirgooo2/MPM">[Code]</a>
    <img alt="NPM" src="https://img.shields.io/github/stars/vvirgooo2/MPM?style=social">
    <br>
    <font color="grey" size="2">
    Treat 2D and 3D pose as two different modalities and apply three mask modeling based pretext tasks for human pose pre-training to learn spatial and temporal
relations.
    </font>
</p>

## Diffusion Model
  <p> 
    <strong>
    StableVideo: Text-driven Consistency-aware Diffusion Video Editing
    </strong>
    <br>
    <b>Wenhao Chai</b>, Xun Guo, Gaoang Wang, Yan Lu
    <br>
    <font color="#E89B00">
    <em>International Conference on Computer Vision (ICCV), 2023</em>
    </font>
    <br>
    <a href="https://rese1f.github.io/StableVideo/">[Website]</a>
    <a href="https://arxiv.org/abs/2308.09592">[Paper]</a>
   	<a href="https://huggingface.co/spaces/Reself/StableVideo">[Demo]</a>
    <a href="https://github.com/rese1f/StableVideo">[Code]</a>
    <img alt="" src="https://img.shields.io/github/stars/rese1f/StableVideo?style=social">
    <br>
    <font color="grey" size="2">
    We tackle introduce temporal dependency to existing text-driven diffusion models, which allows them to generate consistent appearance for the new objects.
    </font>
  </p>

Human Pose Estimation (HPE) is a task focusing on estimating 2D or 3D human keypoints/shapes from images or videos. We aim to develop robust and effective (HPE) pipelines.

- [ZeDO](https://zhyjiang.github.io/ZeDO-proj/): Back to Optimization: Diffusion-based Zero-Shot 3D Human Pose Estimation (WACV 2024)
<p align="center"><img src="images/news/zedo_overall.png" width="50%" alt="" /></p>

## Radar Object Detection
## Domain Adaptation
## Generation for Perception
Use large generative models (e.g. Large Language Models (LLM), Diffusion Models) to aid in perception tasks, including classification, detection and image captioning. Methods are applied in multiple applications, including:
- Human Object Interaction (HOI) Recognition
  - SOTA in HOI classification on HICO: DEFR (Detection-Free HOI Recognition), since 2021
  - SOTA in Zero-shot HOI classification: HTS (Heterogenious Teacher-Student Framework), since 2022
  - SOTA in Zero-shot HOI detection: HTS (Heterogenious Teacher-Student Framework), since 2022
- Medical Image Understanding
  - SOTA in Chest X-ray (CXR) Radiology Report Generation, MIMIC-CXR: C2C (Concept-to-Content Method for Radiology Report Generation), 2023

## LLM

## Continual Learning

## Fish Pose Estimation
