# 🧠 Brain Tumor Detection using GLCM and Logistic Regression

This project implements a brain tumor detection model using **GLCM (Gray-Level Co-occurrence Matrix)** features and a **Logistic Regression** classifier. It processes MRI images labeled as `Tumor` or `Non-Tumor`, extracts texture-based features, and classifies the images with a tested accuracy of **87.50%**.

Each image is converted to grayscale and resized to 128x128 before GLCM feature extraction.

We compute four GLCM-based features per image:
- **Contrast**
- **Energy**
- **Homogeneity**
- **Entropy**
These features help capture the texture variations useful for tumor detection.

## 🧪 Model

- **Classifier**: Logistic Regression (from scratch)
- **Train/Test Split**: 70% training, 30% testing
- **Accuracy Achieved**: **87.50%**
