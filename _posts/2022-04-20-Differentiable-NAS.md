---
toc: false
layout: post
description: 第三阶段第十二次会议 主讲人：郑子维
categories: [NAS]
title: "Differentiable Neural Architecture Search: Challenges and Solutions"
---

## 大纲

### Brief Intorduction to NAS/D-NAS

### Efficient Search Methods
* Differentiable Architecture Sampler (GDAS)
* Partially-Connected DARTS (PC-DARTS)

### Challenge in Optimization
* The performance collapse problem & Early stopping (DARTS+)
* Eliminating unfair advantages (FairDARTS)
* NAS evaluation is frustratingly hard in DARTS search space
* Training on a small proxy 
* Relativistic architecture performance predictor (ReNAS)
* Zero-cost metrics from prune-at-initialization techniques

### Challenge in Selection
* Large curvatures of validation loss w.r.t $\alpha$ (SDARTS)
* The role of dominate eigenvalues $\lambda_{max}^{\alpha}$ of $\nabla_{\alpha}^{2}\mathcal{L}_{valid}$ (R-DARTS)
* The pitfall of magnitude-based selection

### Few-shot NAS & Architecture Distribution
* Few-shot NAS
* Latent architectural distribution

### One-stage NAS & Hardware Deployment
* Direct NAS Without Parameter Retraining (DSNAS)
* Train a once-for-all (OFA) network for hardware deployment

## 视频 & PPT
* 会议录制视频&PPT链接：https://meeting.tencent.com/v2/cloud-record/share?id=7a05f926-04ba-4da7-9888-8e3eec515f94&from=3
