# GAN Training with PyTorch

This repository contains a basic implementation of a Generative Adversarial Network (GAN) using PyTorch. It includes the training code and sample logs showing the progression of discriminator and generator losses during training.

## Project Overview

A GAN consists of two neural networks — a Generator (G) and a Discriminator (D) — competing against each other. The generator tries to create realistic data, while the discriminator tries to distinguish real from fake data. This project demonstrates training a simple GAN from scratch.

## Features

- PyTorch-based GAN implementation
- Training loop with detailed loss logging
- Sample output logs showing loss values per epoch and batch
- Clean code suitable for learning and modification

## Requirements

- Python 3.8+
- PyTorch (version compatible with your CUDA or CPU setup)
- torchvision
- torchaudio (optional depending on your project)

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/<repo-name>.git
   cd <repo-name>
2. Install dependencies:
pip install torch torchvision torchaudio
3. Run the training script:
python train_gan.py
