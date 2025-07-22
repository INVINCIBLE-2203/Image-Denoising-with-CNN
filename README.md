# 🧼 Image Denoising with CNN

This project implements a deep learning-based approach to **image denoising** using a **Convolutional Neural Network (CNN)**. The model is trained to remove synthetic noise from RGB images, restoring them to a cleaner version.

## 🛠️ Features
- Uses a custom CNN for pixel-level noise removal.
- Trained on synthetic noisy-clean image pairs.
- Evaluates model performance using **PSNR** and **SSIM**.
- Visualizes predictions with `matplotlib`.

## 🧩 Dataset
- Input: Noisy RGB images (resized to 300×300).
- Output: Corresponding clean (denoised) images.

## 🚀 Training
- **Epochs**: 150  
- **Loss Function**: Mean Squared Error (MSE)  
- **Optimizer**: Adam  
- **Framework**: TensorFlow / Keras  

## 📊 Evaluation Metrics
- **PSNR (Peak Signal-to-Noise Ratio)** – Measures image quality after denoising.
- **SSIM (Structural Similarity Index)** – Measures structural similarity with ground truth.

## 🖼️ Visual Results
Displays sample denoised images compared to ground truth using `matplotlib`.

## 📁 Project Structure
├── train.py # Model training and evaluation
├── utils.py # Preprocessing and helper functions
├── test/ # Test image dataset
├── results/ # Predicted denoised images
├── test_pixel_values.csv # Optional pixel-level output


## 📦 Dependencies
- TensorFlow
- NumPy
- OpenCV
- Matplotlib
- scikit-image

Install via:
```bash
pip install tensorflow numpy opencv-python matplotlib scikit-image
