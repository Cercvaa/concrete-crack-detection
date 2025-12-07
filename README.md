# 🧱 Concrete Crack Detection with Deep Learning

This project detects cracks in concrete structures using a convolutional neural network (ResNet34 + FastAI).  
It was originally developed and presented as a workshop at the **EYE (European Young Engineers) 55th International Conference**, demonstrating how civil engineers can apply **computer vision and machine learning** to structural health monitoring.

## 📁 Dataset: Concrete Crack Images for Classification

This project uses the publicly available **Concrete Crack Images for Classification** dataset from Kaggle. The dataset consists of 40,000 RGB images of concrete surfaces, with 20,000 images showing cracks and 20,000 showing intact surfaces. Each image is 227×227 px. The original images were collected from real buildings and subsequently processed for classification tasks.  

Dataset URL: https://www.kaggle.com/datasets/arnavr10880/concrete-crack-images-for-classification

## 🎯 Goal

- Build an accessible pipeline for **binary image classification**:
  - `Positive` – images containing cracks.
  - `Negative` – images without cracks.
- Train a deep learning model using **transfer learning**.
- Evaluate performance and export a reusable model for inference / API deployment.

---

## 🗂️ Project Structure

```text
01_concrete_crack_detection.ipynb   # main notebook used in the workshop
models/
  crack_classifier.pkl                # exported FastAI model (optional)
requirements.txt
README.md
