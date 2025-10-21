# Synthetic Image Generation (Deep Learning Final Exam)

This project implements a Generative Adversarial Network (GAN) to generate synthetic images. It compares a baseline GAN with a modified, tuned version.

## 🧠 Overview
This project focuses on building a GAN from scratch, which consists of two competing networks:
1.  **Generator**: Tries to create realistic images from random noise.
2.  **Discriminator**: Tries to distinguish between real images and fake (generated) images.

The project involves building a baseline GAN and then proposing modifications (e.g., architecture tuning, hyperparameter changes) to improve the quality of the generated images, measured by the **Fréchet Inception Distance (FID)**.

## 🧮 Tools & Libraries
- Python
- Jupyter Notebook
- **TensorFlow** & **Keras**
    - `Sequential`, `Model`
    - `Dense`, `Conv2D`, `Conv2DTranspose`, `BatchNormalization`, `LeakyReLU`, `Dropout`
- **NumPy**
- **Matplotlib** (for visualizing generated images)
- **TensorFlow FID** (for evaluation)

## 📊 Features
- Implementation of a baseline GAN.
- Implementation of a modified/improved GAN.
- Training the generator and discriminator in an adversarial loop.
- Qualitative evaluation by observing generated images.
- Quantitative evaluation using the FID score.

## 📁 Files
- `No3_FinalExam_DL.ipynb` → Main Jupyter Notebook with GAN implementations and training logs.
