---
layout: page
title: Chosen-Object Attack
description: Exploiting Hungarian Matching in Detection Transformers
img: assets/img/detr_attack.jpg
importance: 3
category: security
related_publications: wang2025chosen
---

## Overview

The **Chosen-Object Attack** is a novel adversarial attack that exploits vulnerabilities in the Hungarian matching loss used by Detection Transformers (DETR), a modern class of end-to-end object detectors.

## Background

DETR and its variants have gained popularity for eliminating the need for hand-crafted components like NMS and anchor generation. However, their reliance on Hungarian matching for bipartite matching between predictions and ground truth introduces unique vulnerabilities.

## Attack Mechanism

Our attack exploits the assignment mechanism in Hungarian matching to:

1. **Selectively suppress** detection of specific target objects
2. **Manipulate the matching cost matrix** through adversarial perturbations
3. **Achieve high attack success rates** with minimal visual distortion

## Significance

This research exposes critical security flaws in transformer-based object detection systems and highlights the need for robust matching algorithms in safety-critical applications.

## Publication

Under review at IEEE Transactions on Information Forensics and Security (TIFS).
