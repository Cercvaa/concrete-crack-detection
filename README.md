# 🧱 Concrete Crack Detection with Deep Learning

This project detects cracks in concrete structures using a convolutional neural network (ResNet34 + FastAI).  
It was originally developed and presented as a workshop at the **EYE (European Young Engineers) 55th International Conference**, demonstrating how civil engineers can apply **computer vision and machine learning** to structural health monitoring.

## 🎯 Goal

- Build an accessible pipeline for **binary image classification**:
  - `Positive` – images containing cracks.
  - `Negative` – images without cracks.
- Train a deep learning model using **transfer learning**.
- Evaluate performance and export a reusable model for inference / API deployment.

---

## 🗂️ Project Structure

```text
notebooks/
  01_concrete_crack_detection.ipynb   # main notebook used in the workshop
models/
  crack_classifier.pkl                # exported FastAI model (optional)
src/
  inference.py                        # load model & run predictions on new images
data/
  (not committed; see "Dataset" section)
requirements.txt
README.md
