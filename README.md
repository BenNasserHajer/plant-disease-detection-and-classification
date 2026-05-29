# 🌿 Plant Disease Detection & Classification

A complete end-to-end AI system for plant disease detection using **Machine Learning, CNN from scratch, and Deep Learning**, with a real-time deployment using **Gradio on Hugging Face Spaces**.

---

## 📌 Project Overview

This project aims to automatically detect and classify plant leaf diseases from images. It compares multiple AI approaches:

- Classical Machine Learning (handcrafted features)
- CNN built from scratch (custom architecture)
- Transfer Learning (EfficientNetB0 / MobileNetV2)
- Real-time deployment using Gradio

The objective is to evaluate performance differences between traditional feature engineering and deep learning approaches.

---

## 🌱 Dataset

The dataset contains **8 classes** of tomato and potato leaf conditions:

- Tomato Healthy  
- Tomato Early Blight  
- Tomato Late Blight  
- Tomato Leaf Mold  
- Tomato Bacterial Spot  
- Potato Healthy  
- Potato Early Blight  
- Potato Late Blight  

---

## 🧠 Models Implemented

### 🔹 Machine Learning
- Random Forest
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)
- Gradient Boosting

### 🔹 Deep Learning
- CNN from scratch (custom architecture)
- EfficientNetB0 (transfer learning)
- MobileNetV2 (transfer learning)

---

## ⚙️ Pipeline Summary

- Image preprocessing (resize, HSV, grayscale, filters, normalization)
- Segmentation (Canny, Sobel, Otsu, K-Means, Watershed)
- Feature extraction (~201 features)
- Model training (ML + DL)
- Evaluation (accuracy, confusion matrix, ROC curves)
- Interpretability (Grad-CAM)

---

## 📊 Results

The models are evaluated using:

- Accuracy comparison
- Confusion matrices
- ROC curves (multi-class)
- Error analysis
- Grad-CAM visualizations

---

## 🖥️ Gradio Interface

A real-time interface allows users to:

- Upload plant leaf images
- Get predictions from ML + DL models
- View confidence scores
- Visualize Grad-CAM heatmaps

---

## 📸 Screenshots

### 🔍 Gradio Interface
<img width="3401" height="1688" alt="image" src="https://github.com/user-attachments/assets/3441f0a0-e68b-4f9c-bfbe-7f3eff6711b8" />

### 📊 Prediction Result
<img width="1497" height="653" alt="image" src="https://github.com/user-attachments/assets/6aea2389-e39e-47f1-9520-b3663e4a10fa" />

### 🔥 Grad-CAM Visualization
<img width="683" height="1589" alt="image" src="https://github.com/user-attachments/assets/9ae70b98-b1cb-4640-ab8d-26bffc537122" />


---

## 🚀 Deployment (Hugging Face Spaces)

This project is deployed using **Hugging Face Spaces**.
