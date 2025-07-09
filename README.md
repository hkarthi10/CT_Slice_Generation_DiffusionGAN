# CT_Slice_Generation_DiffusionGAN
# Diffusion-GAN for Abdominal CT Slice Synthesis

This project implements a simple Diffusion-GAN model using a U-Net-based architecture for generating synthetic abdominal CT scan slices. It is part of an academic project aimed at exploring generative techniques in medical imaging.

## 🧠 Objective

- Understand and implement a basic Diffusion-GAN pipeline.
- Generate high-quality synthetic CT scan slices.
- Use diffusion-based noise scheduling to train a generative model.

## 📁 Repository Contents

- `Diffusion_GAN_for_Abdominal_CT_Synthesis.ipynb`: Main notebook containing the complete pipeline, training, and visualization.
- `forward-diffusion-scheduler.ipynb`: Handles noise schedule logic.

## 🏗️ Architecture

- **Generator**: U-Net style encoder-decoder.
- **Diffusion Process**: Adds and removes noise over timesteps.
- **Loss**: MSE between predicted and true noise.

## 📊 Results

The model is trained on dummy CT slices and demonstrates the generation of clear synthetic outputs after a few epochs. Final output quality improves with noise scheduling and deeper U-Net layers.

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/hkarthi10/CT_Slice_Generation_DiffusionGAN.git
