---
title: "Retinex Illumination Estimation: Zhang 2011 Paper Replication"
collection: projects
permalink: /projects/retinex-illumination-estimation
excerpt: 'A complete replication of the 2011 Zhang et al. paper on Retinex theory and intrinsic image decomposition for illumination estimation. **Will be adding a video to this soon!**'
date: Released on 2025-07-10
image: 
  path: &image /images/retinex-illumination.jpg
  teaser: /images/retinex-illumination-teaser.jpg
  caption: "Retinex-based illumination estimation and intrinsic image decomposition"
---

## Project Overview
This project is a complete replication of the seminal 2011 paper by Zhang et al. on Retinex theory and intrinsic image decomposition. The work focuses on separating illumination and reflectance components from images, which is fundamental to understanding how lighting affects image appearance and enabling various computer vision applications.

## Technologies Used
- **Python** (NumPy, OpenCV, Matplotlib)
- **Retinex Theory Implementation**
- **Intrinsic Image Decomposition**
- **Gradio** for interactive web interface
- **Image Processing Algorithms**

## Key Features
- **Complete Paper Replication:** Faithful implementation of Zhang et al.'s 2011 methodology
- **Interactive Web Interface:** Upload images and visualize illumination estimation results
- **Intrinsic Image Decomposition:** Separation of illumination and reflectance components
- **Real-time Processing:** Instant visualization of algorithm effects on custom images
- **Educational Implementation:** Clear, well-documented code for learning purposes

## Research Background
Retinex theory, originally proposed by Edwin Land, suggests that human visual perception is based on the ratio of light reflected from different areas rather than absolute light intensity. This theory has applications in:

- **Image Enhancement:** Improving visibility in poorly lit images
- **Computer Vision:** Better understanding of lighting variations
- **Medical Imaging:** Enhanced visualization of medical scans
- **Remote Sensing:** Improved satellite and aerial image analysis

## Algorithm Implementation
The project implements the core Retinex algorithm which:
1. **Estimates Illumination:** Uses multi-scale analysis to estimate the lighting component
2. **Extracts Reflectance:** Computes the reflectance component by removing illumination
3. **Enhances Images:** Applies adaptive processing to improve image quality
4. **Visualizes Results:** Provides side-by-side comparison of original and processed images

## Research Contributions
- Complete replication of Zhang et al.'s 2011 methodology
- Interactive platform for testing Retinex algorithms on custom images
- Educational resource for understanding intrinsic image decomposition
- Practical implementation of classical computer vision theory

## Live Demo
<div style="margin: 20px 0; text-align: center;">
  <a href="https://huggingface.co/spaces/hxriharan/Retinex_Project" target="_blank" class="btn btn--primary">
    <i class="fas fa-external-link-alt"></i> Open Interactive Demo
  </a>
  <p style="margin-top: 10px; color: #666; font-size: 0.9em;">
    Click the button above to open the interactive Retinex Illumination Estimation demo in a new tab
  </p>
</div>

## GitHub
- [Retinex Illumination Estimation Repository](https://github.com/hxriharan/Retinex-Illumination-Estimation-Zhang2011)

## Hugging Face Space
- [Interactive Web Interface](https://huggingface.co/spaces/hxriharan/Retinex_Project)

## Related Research
This work aligns with ongoing research in spectral ratio estimation and physics-based computer vision, combining classical gradient-based methods with modern deep learning approaches for intrinsic image decomposition. 