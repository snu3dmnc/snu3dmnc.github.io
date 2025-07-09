---
title: Targetless LiDAR-Camera Calibration with Anchored 3D Gaussians
date: 2025-05-01

authors:
- SNU Visual & Geometric Intelligence Lab.
image:
  focal_point: 'top'
---

We present a targetless LiDAR-camera calibration method that jointly optimizes sensor poses and scene geometry from arbitrary scenes, without relying on traditional calibration targets such as checkerboards or spherical reflectors. Our approach leverages a 3D Gaussian-based scene representation. We first freeze reliable LiDAR points as anchors, then jointly optimize the poses and auxiliary Gaussian parameters in a fully differentiable manner using a photometric loss. This joint optimization significantly reduces sensor misalignment, resulting in higher rendering quality and consistently improved PSNR compared to the carefully calibrated poses provided in popular datasets. We validate our method through extensive experiments on two real-world autonomous driving datasets, KITTI-360 and Waymo, each featuring distinct sensor configurations. Additionally, we demonstrate the robustness of our approach using a custom LiDAR-camera setup, confirming strong performance across diverse hardware configurations.

<!--more-->

[Project Website](https://zang09.github.io/tlc-calib-site/)