---
title: NIO Autonomous Driving Project (Mar. 2023 – Mar. 2024)
date: 2025-05-12T06:20:15.210Z
draft: false
featured: false
image:
  filename: main_method.jpg
  focal_point: Smart
  preview_only: false
---
<!--StartFragment-->

The project has been successfully concluded. A research paper is currently being prepared for submission to *ACM Transactions on Multimedia Computing, Communications, and Applications (TOMM)*, and the corresponding patent has been filed. This work focuses on **scene flow estimation from 3D point cloud data**, where the input is raw point clouds from arbitrary road scenes, and the output is the estimated velocity vector for each individual point.

To address the challenges of sparse real-world data, we proposed a novel **Point-Flow-Point iterative framework**, which first predicts the scene flow from existing points and then reconstructs missing points based on the predicted flow. This iterative refinement enhances the precision of the estimation. The core architecture integrates **Graph Convolutional Networks (GCN)**, **Point Transformers**, and **Cross-Attention Layers** to extract rich geometric features and compute pointwise similarities for accurate correspondence matching. This enables centimeter-level velocity prediction accuracy under sparse point cloud conditions typical of real-world autonomous driving scenarios.

<!--EndFragment-->