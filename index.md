---
title: "Computer Vision – 3D Reconstruction from Images"
layout: default
---

# 🧠 Computer Vision: 3D Reconstruction from Images

**Author:** Tiago Novello  
**Mentors:** Daniel Perazzo, Vitor Pereira Matias, Diana Aldana?  
**Institution:** Visgraf - IMPA  
**Date:** Aug 3, 2025

---

## 🎯 Objective

The goal of this course is to compute geometric properties of the 3D world from digital images.  
Study classical and learning-based methods for 3D reconstruction, with hands-on implementation and project work.

---

## 📝 Assignments

- Programming, reading, and writing exercises
- Project development following Role and play presentations
- Literature review and problem setup (using Role-Playing Paper-Reading …)
- Iterative development with mentor feedback
- Final presentation at the CG Seminar

---

## 📅 Schedule

### Basics
- **Aug 12** — Introduction  
- **Aug 14** — 3D reconstruction from images using machine learning  

### Scene Representation
- **Aug 19** — Surfaces \[do Carmo\], point clouds, oriented point clouds, meshes  
- **Aug 21** — Implicit surfaces, voxels, SDFs, marching cubes  
  - Implement marching squares using basic primitives  

### Image Formation
- **Aug 26** — Geometric image formation (Camera models: orthographic and perspective)  
  - Implement camera model  
  - Given an RGBD image, compute its point cloud  
  - Implement point cloud rasterization  
- **Aug 28** — Photometric image formation (Plenoptic function, rendering equation)

### Classic 3D Reconstruction: Structure-from-Motion (SfM) \[Szeliski\]
- **Sep 2** — Feature extraction (Harris corner detection, SIFT, …)  
  - Exercise: explore some feature extractor  
- **Sep 4** — Optical flow, feature matching, RANSAC  
  - Exercise: stitching of panoramic images  
- **Sep 9** — Two views SfM \[Zisserman\]  
  - Given sets of corresponding points, find scene points  
  - With and without camera position  
- **Sep 11** — Two views SfM (continued)  
- **Sep 16** — Multi-frame SfM (Bundle adjustment)  
  - Exercise: explore COLMAP  

### Implicit Neural Representations
- **Sep 18** — Implicit neural representations (INRs)  
- **Sep 23** — 3D reconstruction from point clouds (SIREN, IGR, i3D)  
  - Implement: fit a SIREN to an image  
  - Exercise: compute its features using autograd  
- **Sep 25** — Volume rendering (EDO, volume rendering eq, quadrature) \[Max\]

### Neural Radiance Fields (NeRFs)
- **Sep 30** — NeRFs  
  - Implement: given a density function, implement a tiny volume rendering  
- **Oct 2** — NeRFs (continued)  
  - Implement a tiny NeRF  

### Gaussian Splatting
- **Oct 7** — TBD  
- **Oct 9** — Volume splatting  
- **Oct 14** — 3D Gaussian splatting (3DGS)  
- **Oct 16** — 3DGS (continued)  
  - Implement a tiny 3DGS / 2DGS  

### Feed-forward 3D Reconstruction (WiP)
- **Oct 21** — Feed-forward 3D reconstruction (PF-LRM, noposplat)  
  - Visual transformers (ViT), Dinov2  
- **Oct 23** — Feed-forward 3D reconstruction (continued)  
- **Oct 28** — Holiday  
- **Oct 30** — Monocular Depth Estimation (depth anything)  

### Segmentation & Tracking
- **Nov 4** — Segmentation (segment anything)  
- **Nov 6** — Feature Tracking  

---

## 🧪 Projects (WiP)

- **Nov 11** — Project 1 [TBD ?]  
- **Nov 13** — Project 2: NeRF with different architectures (FFN, SIREN, TUNER, FINER)  
  - Mentor: Diana Aldana?  
- **Nov 18** — Project 3: Regularize 3DGS using different depth prediction methods  
  - Mentor: Daniel Perazzo  
- **Nov 20** — Holiday  
- **Nov 25** — Project 4: Initialize NeRF/3DGS using feed-forward 3D reconstruction methods (colmap, Dust3R, noposplat, VGGT)  
  - Mentor: Vitor Pereira Matias  
- **Nov 27** — Project 5 [TBD ?]  

---

## 📚 References

### Lectures
- Silvio Savarese. *Computer Vision, From 3D Perception to 3D Reconstruction and beyond.*
- Andreas Geiger. *Computer Vision.*
- Shree Nayar. *First Principles of Computer Vision.*

### Books
- do Carmo. *Differential geometry of curves and surfaces: revised and updated second edition*
- Hartley and Zisserman. *Multiple View Geometry in Computer Vision.*
- Richard Szeliski. *Computer Vision: Algorithms and Applications 2nd Edition.*
- Torralba et al. *Foundations of Computer Vision*

### Papers
- Max, Nelson. "Optical models for direct volume rendering." TVCG. 2002.

---

_Made with ❤️ by Visgraf @ IMPA_
