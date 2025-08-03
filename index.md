---
title: "Computer Vision – 3D Reconstruction from Images"
layout: default
---

# 🧠 Computer Vision: 3D Reconstruction from Images

**Instructor:** Tiago Novello  
**Contributors:** Daniel Perazzo, Vitor Pereira Matias  
**Institution:** Visgraf - IMPA  
**Semester:** 2025

---

## 🎯 Objective

The goal of this course is to compute geometric and semantic properties of the three-dimensional world from digital images.

---

## 📝 Assignments

- Programming exercises  
- Reading/writing assignments  
- Project development  
- Students will present their work in the **Computer Graphics Seminar**

---

## 📅 Schedule

### Basics
- **Aug 12** — Introduction  
- **Aug 14** — 3D reconstruction from images using machine learning  

### Scene Representation
- **Aug 19** — Surfaces \[do Carmo\], point clouds, oriented point clouds, meshes  
- **Aug 21** — Implicit surfaces, voxels, SDFs, marching cubes  
  - Implement marching squares using primitives  

### Image Formation
- **Aug 26** — Geometric image formation (orthographic and perspective cameras)  
  - Implement camera model  
  - Compute point cloud from RGBD  
  - Point cloud rasterization  
- **Aug 28** — Photometric image formation (Plenoptic function, Rendering equation)

### Classical SfM
- **Sep 2** — Feature extraction (Harris, SIFT, etc.)  
  - Explore feature extractor  
- **Sep 4** — Optical flow, feature matching, RANSAC  
  - Panoramic stitching  
- **Sep 9** — Two-view SfM \[Zisserman\]  
  - Reconstruct scene points with/without known camera positions  
- **Sep 11** — Two-view SfM (continued)  
- **Sep 16** — Multi-frame SfM (Bundle adjustment)

---

## 🧠🧱🚜 Implicit Neural Representations
- **Sep 18** — Implicit neural representations (INRs)  
- **Sep 23** — 3D reconstruction from point clouds (SIREN, IGR, i3D)  
  - Fit a SIREN to an image  
  - Extract features with autograd  
- **Sep 25** — Volume rendering (ODEs, volume eq., quadrature) \[Max\]

---

## 🟡🌐🫧 Neural Radiance Fields (NeRF)
- **Sep 30** — NeRFs  
  - Implement tiny volume renderer from a density function  
- **Oct 2** — NeRFs (continued)  
  - Implement a tiny NeRF

---

## 🌐🫒🫧 Gaussian Splatting
- **Oct 7** — *TBA*  
- **Oct 9** — Volume splatting  
- **Oct 14** — 3D Gaussian splatting (3DGS)  
- **Oct 16** — 3DGS (continued)  
  - Implement a tiny 3DGS / 2DGS

---

## ⚡️ Feed-forward 3D Reconstruction
- **Oct 21** — PF-LRM, noposplat  
  - Visual transformers (ViT), DINOv2  
- **Oct 23** — Feed-forward continued  
- **Oct 28** — *Holiday*  
- **Oct 30** — Monocular depth estimation (e.g., Depth Anything)

---

## 🧩 Segmentation & Tracking
- **Nov 4** — Segmentation (e.g., Segment Anything)  
- **Nov 6** — Feature tracking  
  - *(TODO: choose paper)*

---

## 🧪 Projects (in progress)

- **Nov 11** — Project 1: Classic vision  
- **Nov 13** — Project 2: NeRF  
  - Use different architectures  
- **Nov 18** — Project 3: 3DGS  
  - Regularize with monocular depth  
- **Nov 20** — *Holiday*  
- **Nov 25** — Project 4: Feed-forward  
  - Initialize NeRF/3DGS with Dust3R, noposplat, VGGT, etc.  
  - Can we replace COLMAP?  
- **Nov 27** — Project 5: Generative

---

## 📚 References

### 🎓 Lectures
1. Silvio Savarese – *Computer Vision, From 3D Perception to 3D Reconstruction and beyond*  
2. Andreas Geiger – *Computer Vision*  
3. Shree Nayar – *First Principles of Computer Vision*

### 📘 Books
4. do Carmo – *Differential Geometry of Curves and Surfaces*  
5. Hartley & Zisserman – *Multiple View Geometry in Computer Vision*  
6. Richard Szeliski – *Computer Vision: Algorithms and Applications*  
7. Torralba et al. – *Foundations of Computer Vision*

### 🧾 Papers
8. Max, Nelson – *Optical Models for Direct Volume Rendering* (TVCG 2002)

---

### 🌐 Additional Links
- [Stanford CS231A](https://web.stanford.edu/class/cs231a/syllabus.html)  
- [Tübingen Computer Vision](https://uni-tuebingen.de/.../computer-vision)  
- [Columbia FPCV](https://fpcv.cs.columbia.edu)  
- [Zisserman Book PDF](https://www.r-5.org/.../Multiple_View_Geometry...)  
- [Szeliski Book Online](https://szeliski.org/Book/)  
- [MIT Vision Book](https://visionbook.mit.edu)

---

_Made with ❤️ by Visgraf @ IMPA_
