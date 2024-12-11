# Image-Denoising-using-Autoencoder-and-PCA-ML-course
This project implements image denoising techniques using Autoencoders and Principal Component Analysis (PCA). The goal is to compare the effectiveness of neural network-based and statistical approaches in removing noise from images.

## Overview
Image denoising is an essential preprocessing step in computer vision and image analysis. This project leverages two approaches:

1. **Autoencoder**: A type of neural network trained to reconstruct input data while minimizing noise. The autoencoder learns a compressed representation of the image, which is used for denoising.

2. **PCA (Principal Component Analysis)**: A statistical technique used to reduce dimensionality and extract the principal features of an image while discarding noise.

## Dataset
The project utilizes a standard image dataset such as:
- MNIST

Each image is corrupted by adding synthetic noise (e.g., Gaussian noise), simulating real-world scenarios.

## Implementation Steps

1. **Data Preprocessing**:
   - Normalize image pixel values.
   - Add synthetic noise to create noisy input images.

2. **Autoencoder-Based Denoising**:
   - Construct an autoencoder using TensorFlow/Keras.
   - Train the autoencoder to minimize reconstruction loss.
   - Evaluate the denoised output.

3. **PCA-Based Denoising**:
   - Reshape images into vectors.
   - Apply PCA to reconstruct images with reduced noise.

4. **Comparison**:
   - Evaluate both methods using metrics like PSNR (Peak Signal-to-Noise Ratio) and MSE (Mean Squared Error).

## Results
- Visual and quantitative comparison of denoising results.
- Analysis of strengths and weaknesses of each method.

