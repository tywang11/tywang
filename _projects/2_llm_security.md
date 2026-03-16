---
layout: page
title: LLM Serving Security
description: Rethinking Denial-of-Service in LLM Inference Systems
img: assets/img/llm_security.jpg
importance: 2
category: security
related_publications: wang2025llm
---

## Overview

This project investigates **denial-of-service vulnerabilities in LLM serving systems**, revealing new attack surfaces that can exploit the unique characteristics of transformer-based inference pipelines.

## Research Questions

- How can attackers exploit scheduling mechanisms in LLM serving systems?
- What are the implications of prefix caching on system availability?
- How do batching strategies affect system robustness under adversarial workloads?

## Key Findings

Our analysis reveals that LLM serving systems are vulnerable to novel attack vectors that target:

1. **KV Cache Manipulation**: Exploiting memory pressure in the key-value cache
2. **Scheduling Exploits**: Crafting requests that maximize scheduling overhead
3. **Batch Size Attacks**: Forcing suboptimal batch configurations

## Impact

This work provides critical insights for designing robust LLM serving infrastructure that can maintain availability under adversarial conditions.

## Publications

Submitted to USENIX ATC 2025.
