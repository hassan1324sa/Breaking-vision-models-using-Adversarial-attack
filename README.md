# Breaking Vision Models using Adversarial Attacks 🔍🎯

![Adversarial Example Demo](assets/demo.gif) <!-- Replace with your own GIF/image -->

This repository demonstrates how adversarial attacks can fool state-of-the-art vision models (e.g., CNNs) by adding imperceptible perturbations to input images. Implementations include **FGSM**, **PGD**, and custom attacks to test model robustness. Ideal for researching vulnerabilities in deep learning systems.

---

## Table of Contents
- [Key Features](#key-features)
- [Installation](#installation)
- [Quick Start](#quick-start)
- [Attack Methods](#attack-methods)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)
- [References](#references)

---

## Key Features 🚀
- **Attack Algorithms**: 
  - **FGSM** (Fast Gradient Sign Method)
  - **PGD** (Projected Gradient Descent)
  - **CW Attack** (Carlini-Wagner)
  - Customizable perturbation constraints (L∞, L2 norms).
- **Supported Models**: 
  - Pretrained PyTorch models (ResNet, VGG, DenseNet).
  - Custom models (easy integration).
- **Datasets**: CIFAR-10, ImageNet, MNIST, and custom datasets.
- **Visualization**: Tools to compare adversarial/original images and confidence scores.

---

## Installation 🛠️

1. **Clone the repo**:
   ```bash
   git clone https://github.com/hassan1324sa/Breaking-vision-models-using-Adversarial-attack.git
   cd Breaking-vision-models-using-Adversarial-attack
