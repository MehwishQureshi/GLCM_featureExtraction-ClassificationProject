## 🧠 Brain Tumor Classification using GLCM and Logistic Regression
This project implements an image classification pipeline using GLCM (Gray Level Co-occurrence Matrix)-based texture feature extraction combined with traditional machine learning — specifically, Logistic Regression — to detect and classify brain tumors from MRI images.

## Dataset Description
- Dataset : Brain Tumor MRI Dataset from Kaggle
- Dataset Link : (https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset)
- Total Images: 7023
- Classes (4): **glioma, meningioma, pituitary and no_tumor**

The dataset is organized into Training and Testing folders, each with class-wise subfolders.
All images are grayscale brain MRI scans with varying sizes, intensities, and contrast levels.

## Objective
To build a multi-class image classification model that can identify brain tumors using texture features extracted via GLCM and classify them into one of the four tumor types using Logistic Regression.

## 📌 Key Concepts
- GLCM (Gray Level Co-occurrence Matrix) : Captures spatial relationships of pixels and is useful for extracting texture-based features like : **Contrast, Dissimilarity, Homogeneity, Energy, Correlation, ASM (Angular Second Moment)**

- Logistic Regression (Multinomial) : A traditional, interpretable classification algorithm applied to extracted features for final prediction.

## Tools & Libraries
- Python 3
- OpenCV – for image loading and preprocessing
- Matplotlib - for visualizations

📈 Model Performance
- Classifier : Logistic Regression (Multinomial)
- Classification Type: Multi-class (4 categories)
- Test Accuracy : ⚠️ 51.41%

**Note: Accuracy is moderate due to limited feature representation. GLCM works well for texture but may not capture all spatial/structural details needed for high-accuracy classification. Improvement is possible using CNNs or advanced feature engineering.**
