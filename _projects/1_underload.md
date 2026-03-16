---
layout: page
title: Underload
description: Hardware-Adaptive Defense against Latency Attacks on Edge Devices
img: assets/img/underload.jpg
importance: 1
category: security
related_publications: wang2025underload
---

## Overview

**Underload** is a hardware-adaptive, background-attentive adversarial training mechanism designed to defend against latency attacks on real-time object detection systems deployed on edge devices.

## Problem

Latency attacks exploit the computational bottleneck in the Non-Maximum Suppression (NMS) module by generating thousands of "phantom objects" through adversarial perturbations. This can degrade real-time processing capability from 30+ FPS to as low as 13 FPS on edge devices, putting critical applications like autonomous driving at risk.

## Key Contributions

1. **System-level Analysis**: Discovered bottleneck migration patterns between edge and desktop GPUs, from compute-bound to memory-bound operations.

2. **Objectness Loss as Proxy**: Utilized objectness loss to effectively eliminate phantom objects while maintaining detection accuracy.

3. **Background-Attentive AT**: Designed an adversarial training mechanism that weighs more on background semantics to achieve better balance between robust and clean accuracy.

## Results

- Restored real-time capability from **13 FPS to 43 FPS** on Jetson Orin NX
- Achieved **8-10% improvement** in robust accuracy compared to existing defenses (MTD, OOD)
- Validated across YOLOv3, YOLOv5, and YOLOv8 on multiple GPU platforms:
  - Embedded: Jetson Xavier, Jetson Orin NX
  - Desktop: RTX 4070Ti Super
  - Cloud: NVIDIA A100

## Code

[GitHub Repository](https://github.com/Hill-Wu-1998/underload)
