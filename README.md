
# Image Denoising using a Convolutional Autoencoder

Project Overview

This project demonstrates a computer vision solution for image restoration, specifically removing Gaussian noise from images using a deep learning model. A **Convolutional Autoencoder** was developed to learn the features of clean images and reconstruct them from noisy versions.

The methodology involved a comparative analysis of three different autoencoder architectures:
1.  A **Baseline Autoencoder** to set a performance benchmark.
2.  A **Manually Modified Autoencoder** with an increased filter capacity.
3.  A **Hyperparameter-Tuned Autoencoder**, optimized using the KerasTuner library.

The effectiveness of each model in restoring the images was quantitatively measured using the **Structural Similarity Index Measure (SSIM)**.

Technologies Used
- Python
- TensorFlow / Keras
- KerasTuner
- NumPy
- Matplotlib

Dataset
The project uses the **Pistachio Image Dataset**. Gaussian noise was programmatically added to the images to create a noisy dataset for training the autoencoder to perform the denoising task.

How to Run this Project
1. Clone the repository to your local machine:
   ```bash
   git clone [https://github.com/geraldusjeremy/Image-Denoising-using-a-Convolutional-Autoencoder-with-KerasTuner.git](https://github.com/geraldusjeremy/Image-Denoising-using-a-Convolutional-Autoencoder-with-KerasTuner.git)
