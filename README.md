# Denoising Autoencoders for Image Reconstruction
*A Machine Learning & Neural Networks Coursework Project*

---

## Course Information

**Course:** 7PAM2021 — Machine Learning & Neural Networks  
**Tutorial Topic:** Denoising Autoencoders for Image Reconstruction  
**Student Name:** Muhammad Wasal Imtiaz  
**Student ID:** 24077342  

---

## Project Overview

This repository contains the implementation and tutorial code for a **Convolutional Denoising Autoencoder (DAE)** trained on the **MNIST handwritten digits dataset**.

The goals of this project are to:

- Explain autoencoders and their purpose  
- Demonstrate why *denoising autoencoders* are effective for robust feature learning  
- Build and train a convolutional DAE in Keras/TensorFlow  
- Compare original, noisy, and reconstructed images  
- Generate training curves and latent feature visualisations  
- Support the written PDF tutorial submitted for coursework  

This project was completed as part of the Machine Learning & Neural Networks module.

---

## What is a Denoising Autoencoder?

A denoising autoencoder (DAE) learns to reconstruct clean inputs from intentionally corrupted data.

It works in three main steps:

1. **Encoding** — compressing input into a latent representation  
2. **Noise removal** — learning robust features  
3. **Decoding** — reconstructing a clean version of the input  

In this project, MNIST digits were corrupted with Gaussian noise, and the DAE learned to recover the clean digits.

---

## Repository Contents

| File | Description |
|------|-------------|
| `Machine_Learning_Tutorial.ipynb` | Full implementation, model training, visualisations, and explanations |
| `README.md` | Project overview and instructions |
| `LICENSE` | MIT License file |

---

## How to Run the Notebook

### 1. Install dependencies

```bash
pip install tensorflow keras matplotlib numpy
