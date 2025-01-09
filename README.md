# Facial Recognition Using Eigenfaces

This project implements a facial recognition system leveraging **Eigenfaces** for dimensionality reduction and **1-Nearest Neighbor (1NN)** for classification. By projecting facial images onto a reduced-dimensional "face space," the system demonstrates efficient recognition of grayscale facial images.

---

## Project Highlights
- **Dimensionality Reduction**: Used **Principal Component Analysis (PCA)** to transform high-dimensional facial images into a compact "face space."
- **Classification**: Applied a simple yet effective **1-Nearest Neighbor (1NN)** classifier for recognizing facial images.
- **Experiments**: Explored the impact of image resizing on recognition accuracy by comparing original (`112x92`) and resized (`56x46`) image dimensions.
- **Cross-Validation**: Performed **5-fold cross-validation** to ensure robust evaluation of the model's performance.

---

## Dataset Overview
- **Dataset Size**: 400 grayscale images of 40 subjects (10 images per subject).
- **Image Dimensions**:
  - Original: `112x92 pixels`
  - Resized: `56x46 pixels`
- **Splitting**:
  - **Training Set**: 50 images per class.
  - **Testing Set**: 5 images per class.
- **Preprocessing**:
  - Images were resized, centered, normalized, and flattened into vectors for PCA transformation.
- **Dataset Source**: Custom or available in the project directory.

---

## Technologies and Tools
- **Programming Language**: Python
- **Libraries**:
  - `NumPy`: Numerical computations for PCA and linear algebra.
  - `OpenCV` or `Pillow`: Image processing and resizing.
  - `Matplotlib`: Visualizations (e.g., Eigenfaces, accuracy plots).
  - `Scikit-learn`: Utilities for PCA and cross-validation.

---
