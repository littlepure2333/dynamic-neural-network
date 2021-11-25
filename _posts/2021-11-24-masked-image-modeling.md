---
toc: false
layout: post
description: 第三阶段第三次会议 主讲人：韩益增
categories: [Masked Image Modeling]
title: Masked Image Modeling for Unsupervised Representation Learning
---
## 大纲

* iGPT

  * Low resolution
  * Auto-regressive & MIM
  * Transformer (not ViT)
  * Mask 20% patches
  * Prove that it works
* BeiT

  * High resolution
  * MIM
  * ViT
  * Tokenization with discrete VAE
  * Mask 40% patches
  * Masked patches are fed to the encoder
* MAE

  * High resolution
  * MIM
  * ViT
  * Direct reconstruct the masked raw pixels
  * MSE Loss
  * Only unmasked patches are fed to the encoder
  * Mask 75% patches
  * Lightweight Transformer as decoder
* SimMIM

  * High resolution
  * MIM
  * ViT and Swin-V2
  * Direct reconstruct the masked raw pixels
  * L1 Loss
  * Only unmasked patches are fed to the encoder
  * Mask 10~90% patches (50 works best)
  * One linear layer as decoder

## 视频&PPT

视频：https://meeting.tencent.com/v2/cloud-record/share?id=76081824-93e9-406f-9c73-e4b4d6f1fa91&from=3

Slide: 链接: https://pan.baidu.com/s/1YuZT1dHKTUy2AqhoVelpHA 提取码: bv9c
