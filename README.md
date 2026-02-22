# 📚 Reproducing Research Results (RRR) – CVPR & MICCAI 2024

## 🔬 Overview

This repository contains a structured reproducibility study of **8 peer-reviewed papers from CVPR 2024 and MICCAI 2024**, spanning:

* Diffusion-based generative modeling
* Transformer-based object detection
* 3D perception and point cloud learning
* Self-supervised motion prediction
* Medical vision-language robustness
* Hyperspectral and inverse imaging reconstruction

The goal of this project was to reconstruct experimental pipelines, validate benchmark results, and analyze reproducibility challenges in state-of-the-art computer vision and medical AI research.

---

## 📄 Reproduced Papers

### CVPR 2024

1. **F3Loc: Fusion and Filtering for Floorplan Localization**
   → Probabilistic filtering, multi-view geometry, sequential localization

2. **Learned Representation-Guided Diffusion Models for Large-Image Generation**
   → SSL-conditioned diffusion, patch-based synthesis, FID evaluation

3. **Hybrid Proposal Refiner: Revisiting DETR Series from the Faster R-CNN Perspective**
   → Transformer-based object detection refinement

4. **Self-Supervised Class-Agnostic Motion Prediction with Spatial and Temporal Consistency Regularizations**
   → Optimal transport, pseudo-labeling, LiDAR motion prediction

5. **Dual Prior Unfolding for Snapshot Compressive Imaging**
   → Deep unfolding, Swin Transformers, hyperspectral reconstruction

6. **CDFormer: When Degradation Prediction Embraces Diffusion Model for Blind Image Super-Resolution**
   → Diffusion priors for blind SR, benchmark validation

7. **RepKPU: Point Cloud Upsampling with Kernel Point Representation and Deformation**
   → Kernel-based geometric learning, Chamfer-based evaluation

---

### MICCAI 2024

8. **PromptSmooth: Certifying Robustness of Medical Vision-Language Models via Prompt Learning**
   → Randomized smoothing, certified robustness, zero-shot & few-shot adaptation

---

## 🧠 Technical Coverage

This project involved implementing and validating:

* Diffusion-based generative models
* Transformer architectures in vision
* Transformer-based object detection
* Self-supervised representation learning
* 3D point cloud learning
* Vision-language modeling
* Adversarial and certified robustness
* Optimal transport & geometric learning
* Deep unfolding & inverse problems
* Multi-view geometry
* Probabilistic filtering

---

## 📊 Benchmarks & Evaluation

Experimental validation was performed across multiple datasets and benchmarks, including:

* COCO
* NuScenes
* CAVE_1024
* Gibson
* Medical imaging subsets
* Standard super-resolution benchmarks (Set5, Set14, Urban100, BSDS100)

Evaluation metrics include:

* PSNR / SSIM
* FID
* Chamfer Distance
* Recall@Threshold
* Motion prediction error
* Certified accuracy under randomized smoothing

---

## ⚙️ Reproducibility Scope

For each paper, the following were reconstructed:

* Environment setup (PyTorch, CUDA, Conda)
* Dependency resolution
* Dataset preprocessing
* Training and evaluation pipelines
* Metric validation against reported benchmarks

Where necessary, distributed pipelines were adapted to single-GPU execution and version conflicts were resolved to ensure reproducible execution.

---

## 🎯 Project Objective

This repository serves as a structured exploration of:

* Experimental reproducibility in modern deep learning
* Implementation fidelity of state-of-the-art models
* Practical challenges in replicating research results
* Cross-domain architectural understanding

The project emphasizes **methodological reconstruction and benchmark validation**, rather than proposing novel methods.

---

## 📌 Repository Structure

```
.
├── F3Loc/
├── Large-Image-Diffusion/
├── HPR/
├── SelfMotion/
├── DPU/
├── CDFormer/
├── RepKPU/
├── PromptSmooth/
└── README.md
```

Each folder contains environment notes, execution scripts, and reproduction documentation specific to the corresponding paper.

---

## 🧾 License & Disclaimer

This repository reproduces publicly available research for educational and research validation purposes.
All original methods and contributions belong to their respective authors.
