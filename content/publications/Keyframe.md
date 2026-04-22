---
title: 'Keyframe Selection from Motion Capture Data with Dual-Agent Reinforcement Learning'
date: 2026-04-18T00:00:00+00:00
description: "Hu, Kun, **Xinzhi Wang**, Clinton A. Mo, Mingyang Ma, Shaohui Mei, Zebin Chen, and Zhiyong Wang. \"Keyframe selection from motion capture data with dual-agent reinforcement learning.\" Pattern Recognition 179 (2026): 113775."
tags: ["reinforcement learning", "motion capture", "animation"]
type: post
showTableOfContents: true
badge: "Pattern Recognition 2026"
badgeClass: "journal"
---

## :page_with_curl: Abstract
Animation production workflows centered around motion capture techniques require animators to edit motions based on a set of keyframes. However, most existing keyframe selection methods are optimization-based, which suffer from limitations in flexibility and efficiency. 

In this paper, we propose a novel deep reinforcement learning framework with dual agents for unsupervised keyframe selection. Specifically, an S-Agent is responsible for selection, while an R-Agent performs refinement. Both agents are powered by a deep spatio-temporal model, the Graph Keyframe Evaluation Network (GKEN). 

We further design an animation-specific reward based on reconstruction that satisfies three key properties important for animation workflows: incremental reward, order insensitivity, and non-diminishing returns. Notably, during inference, reconstruction is no longer required, significantly reducing runtime latency. 

Experiments on the CMU MoCap dataset demonstrate that our method achieves strong efficiency gains while maintaining competitive effectiveness compared to state-of-the-art approaches.

## :file_cabinet: Paper
https://www.sciencedirect.com/science/article/pii/S0031320326007405

## :bookmark: Citation