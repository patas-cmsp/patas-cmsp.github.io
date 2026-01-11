---
layout: "default"
title: "🎈 ComfyUI-LG_SamplingUtils - Enhance Your Sampling Experience"
description: "🎈 Enhance your ComfyUI experience with robust sampling nodes for advanced techniques in Flow Matching models like ZImage and Lumina2."
---
# 🎈 ComfyUI-LG_SamplingUtils - Enhance Your Sampling Experience

[![Download](https://img.shields.io/badge/Download-v1.0-blue.svg)](https://github.com/patas-cmsp/ComfyUI-LG_SamplingUtils/releases)

![Image](./assets/1.jpg)

[中文文档](README_CN.md) | **English**

---

## 📖 Overview

**ComfyUI-LG_SamplingUtils** offers a set of tools designed for ComfyUI by LAOGOU-666. It provides useful sampling nodes that make your work easier and more effective. This extension specializes in advanced sampling methods, especially optimized for Flow Matching models like ZImage and Lumina2.

## ⚙️ Features

This extension includes four key nodes to improve your workflow:

### 1. 🎈 ZImage Timestep Noise

This node adds noise to timesteps during sampling. This helps break model uniformity and creates more varied outputs.

**Key Features:**
- Two modes: `sigma` (used in traditional diffusion models) and `flow` (suitable for Flow Matching models).
- Adjustable noise strength and application range.
- Optional mask for targeted effects.
- Seed-based reproducibility for consistent results.

**Parameters:**
- `mode`: Select from `sigma` (multiplicative noise) or `flow` (additive noise).
- `noise_strength`: Control how much noise to apply.

### 2. 🌊 Flow Matching Samples

This node focuses on generating samples that align closely with your target images. It optimizes the rendering process.

**Key Features:**
- High fidelity to target images.
- Fast processing speed.
- Easy integration with existing workflows.

**Parameters:**
- `target_image`: Input image for alignment.
- `sample_count`: Number of samples to produce.

### 3. 🛠 Optimization Nodes

These nodes improve the performance of your models, making them faster and more efficient.

**Key Features:**
- Auto-tuning for optimal performance.
- Reduce computation time while maintaining quality.

**Parameters:**
- `optimization_level`: Define how aggressive to optimize.

### 4. 📊 Result Visualization

This node helps you visualize samples in real time, making it easier to interpret results.

**Key Features:**
- Supports multiple visualization formats.
- Interactive features for detailed analysis.

**Parameters:**
- `visualization_type`: Choose your preferred format (graph, table, etc.).
- `refresh_rate`: Set how frequently to update visualizations.

## 🔍 System Requirements

Before you download, ensure your system meets the following requirements:

- Operating System: Windows 10 or later / macOS 10.14 or later
- RAM: Minimum 8GB (16GB recommended)
- Disk Space: At least 1GB available
- Required Software: .NET Framework 4.7.2 or later

## 🚀 Getting Started

Follow these steps to get started with **ComfyUI-LG_SamplingUtils**:

1. **Visit the Releases Page:**
   Go to the [Releases page](https://github.com/patas-cmsp/ComfyUI-LG_SamplingUtils/releases).

2. **Download the Latest Version:**
   Find the latest release and click on it to view available assets. Look for a file named similar to `ComfyUI-LG_SamplingUtils_v1.0.zip` and download it.

3. **Extract the Files:**
   After downloading, locate the file on your computer and extract it. This can be done by right-clicking the zip file and selecting "Extract All".

4. **Run the Application:**
   Inside the extracted folder, look for the executable file named `ComfyUI-LG_SamplingUtils.exe`. Double-click this file to start the application.

5. **Follow On-Screen Instructions:**
   Once the application is running, follow the on-screen instructions to set up and start sampling.

## 📥 Download & Install

To download the software, please visit the [Releases page](https://github.com/patas-cmsp/ComfyUI-LG_SamplingUtils/releases). Download the latest version and follow the installation instructions above.

## 📞 Support

If you encounter any issues or need assistance, please check the [GitHub Issues page](https://github.com/patas-cmsp/ComfyUI-LG_SamplingUtils/issues) for solutions or to file a new issue.

## 📜 License

This project is licensed under the MIT License. For more details, check the LICENSE file in the repository.

---

Feel free to contribute to this project. Your feedback and suggestions are welcome.