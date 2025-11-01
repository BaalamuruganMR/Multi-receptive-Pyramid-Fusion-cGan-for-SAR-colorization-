# Multi-receptive-Pyramid-Fusion-cGan-for-SAR-colorization-
Conditional GAN-based model for SAR image colorization using ASPP and FPN modules, capturing multi-scale features and preserving fine details for realistic, interpretable SAR-to-optical translation in remote sensing applications.
# 🛰️ Conditional GAN for SAR Image Colorization using ASPP & FPN

This repository implements a **Conditional Generative Adversarial Network (cGAN)** for **colorizing Synthetic Aperture Radar (SAR) images**, leveraging a hierarchical architecture that integrates **Atrous Spatial Pyramid Pooling (ASPP)** and **Feature Pyramid Network (FPN)** modules.

---

## 🧠 Project Overview

SAR images are vital in remote sensing and Earth observation, but their grayscale nature limits interpretability.  
This project aims to **colorize SAR images** by learning mappings from SAR to optical domains using a deep generative approach.

- The **Generator** uses **ASPP** to capture multi-scale spatial features and **FPN** to fuse fine and global contextual details.  
- The **Discriminator** employs **Pyramid Atrous Convolution** for robust evaluation of image realism and structural consistency.  

Training utilizes **paired SAR–optical datasets** with a **composite loss function** combining:
- Adversarial Loss  
- Perceptual Loss  
- Pixel-wise (L1/L2) Loss  

---

## 🚀 Features

- Conditional GAN for SAR image colorization  
- ASPP + FPN integration for multi-scale and hierarchical feature learning  
- Pyramid Atrous Convolution-based discriminator  
- Hybrid loss for realistic and consistent colorization  
- Supports custom SAR–optical datasets  
- Visual comparison of generated vs. real optical images  

