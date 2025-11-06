# 🧠 GANs from Scratch (PyTorch Implementation)
This notebook, GANs_from_scratch.ipynb, demonstrates how to implement a Generative Adversarial Network (GAN) completely from scratch using PyTorch.
It walks through every key step — from building the generator and discriminator models to training the network and visualizing generated samples.

## 📘 Overview

A Generative Adversarial Network (GAN) consists of two neural networks that compete with each other:

  - Generator (G): Learns to produce realistic fake data from random noise.

  - Discriminator (D): Learns to distinguish between real and fake data.

Through this adversarial process, the generator improves at producing data that closely resembles the real dataset.

## 🧩 Notebook Structure
```bash
| Section                            | Description                                        |
| ---------------------------------- | -------------------------------------------------- |
| 1. Introduction                    | Overview of GANs and PyTorch setup                 |
| 2. Generator and Discriminator     | Definition of model architectures                  |
| 3. Training Loop                   | Implementation of the adversarial training process |
| 4. Visualization                   | Displaying generated images as training progresses |
| 5. Results                         | Final outputs and discussion                       |
```
## ⚙️ Requirements
To run this notebook, install the following dependencies:
```bash
pip install torch torchvision matplotlib pytorch-lightning
```

## Recommended environment:
 - Python ≥ 3.10
 - PyTorch ≥ 2.0
 - PyTorch Lightning ≥ 2.0
 - GPU (CUDA) is highly recommended

## 🚀 How to Run
Clone the repository:
```bash
git clone https://github.com/ms20237/GANs.git
cd GANs
```
Launch Jupyter:
```bash
jupyter notebook GANs_from_scratch.ipynb
```

## License

This project is licensed under the [MIT License](https://choosealicense.com/licenses/mit/).

