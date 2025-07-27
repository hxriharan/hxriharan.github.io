---
title: "AR-Based 3D Scene Reconstruction from Multi-View Images"
collection: projects
permalink: /projects/ar-3d-reconstruction
excerpt: 'A from-scratch Structure-from-Motion pipeline using C++, OpenCV, and Ceres for AR-based 3D reconstruction from phone-captured multi-view RGB images.'
date: 2025-04-25
image: 
  path: &image /images/ar-reconstruction.jpg
  teaser: /images/ar-reconstruction-teaser.jpg
  caption: "Multi-view 3D point cloud reconstruction using phone images"
---

## Project Overview
Implemented a complete AR-based 3D reconstruction pipeline using Structure-from-Motion principles. The system reconstructs a 3D point cloud from multi-view phone images using SIFT features, pose chaining, triangulation, and bundle adjustment.

## Technologies Used
- **C++ / OpenCV**
- **Ceres Solver** for bundle adjustment
- **SIFT Feature Detection**
- **Open3D** for point cloud visualization

## Key Features
- Custom pose chaining and triangulation logic
- Accurate camera calibration from phone EXIF data
- Experimental integration of MiDaS for dense depth fusion
- IEEE-format report and video presentation included

## Research Contributions
- End-to-end SfM pipeline implemented from scratch
- Evaluation against COLMAP and MiDaS-based baselines
- Insights on 3D reconstruction accuracy from mobile sensors

## Video Presentation
<div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%; margin: 20px 0;">
  <iframe src="https://www.youtube.com/embed/FcqunFPUi5g?autoplay=1&mute=1" 
          style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; border: 0;" 
          allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
          allowfullscreen>
  </iframe>
</div>

## GitHub
- [AR-Based 3D Scene Reconstruction](https://github.com/hxriharan/AR-Based-3D-Scene-Reconstruction-from-Multi-View-Images)
