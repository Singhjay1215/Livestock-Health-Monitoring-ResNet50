# Livestock Health Monitoring System using ResNet50

## 📌 Project Overview

This project is a Deep Learning-based Livestock Health Monitoring System designed to classify livestock images into:

- 🟢 Healthy
- 🔴 Lumpy Skin Disease (LSD)

The system uses a **ResNet50-based Convolutional Neural Network (CNN)** model for image classification and provides a simple **Gradio web interface** for uploading livestock images and receiving predictions.

## 🎯 Objective

The main objective of this project is to assist in the early identification of Lumpy Skin Disease in livestock using computer vision and deep learning.

The system takes an image as input and predicts whether the livestock appears:

**Healthy** or **affected by Lumpy Skin Disease.**

## 🧠 Model

The project uses **ResNet50**, a deep convolutional neural network architecture commonly used for image classification.

### Model Input

- Image size: `224 × 224`
- Channels: `RGB`
- Input shape: `(224, 224, 3)`

### Output

The model produces a probability for Lumpy Skin Disease.

```text
Probability >= 0.5  →  Lumpy Skin Disease
Probability < 0.5   →  Healthy
