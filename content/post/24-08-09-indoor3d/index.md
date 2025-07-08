---
title: Capturing & Free-viewpoint rendering of Haedong plaza
date: 2024-06-12
authors:
- SNU 3D Vision Lab.
image:
  focal_point: 'top'
---

Development of cutting-edge deep learning technology for 3D reconstruction using only a few-shot of images.

<!--more-->

Capturing complex architectural environments for immersive visualization is traditionally labor-intensive and computationally expensive. In this project, we present a fast, accessible, and high-quality 3D capture pipeline for Haedong Plaza, leveraging omnidirectional video and neural rendering techniques to enable realistic free-viewpoint navigation.

We employed NeRF-based rendering techniques to reconstruct and visualize the 3D scene:
	•	Proposal network sampling from Mip-NeRF 360 for efficient training in unbounded scenes.
	•	Pose refinement for accurate camera localization.
	•	Multi-resolution hash grids from Instant-NGP for memory-efficient representation

{{< youtube Wa9vlX4ABng>}}

The final output is a smooth and immersive rendering of Haedong Plaza from arbitrary viewpoints. The visualization faithfully captures complex geometry and lighting, demonstrating the pipeline’s viability for large indoor architectural spaces