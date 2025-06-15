# 🧠 CIFAR-10 Image Classification using TensorFlow

This project demonstrates how to build and train a Convolutional Neural Network (CNN) to classify images from the [CIFAR-10 dataset](https://www.cs.toronto.edu/~kriz/cifar.html) using **TensorFlow** and **Keras** on **Google Colab**.

---

## 🚀 Project Overview

- Classifies 32×32 color images into 10 object categories:
  `airplane`, `automobile`, `bird`, `cat`, `deer`, `dog`, `frog`, `horse`, `ship`, `truck`
- Built and trained a CNN from scratch using TensorFlow
- Achieved ~75–80% accuracy on the test dataset
- Visualized model predictions on test images

---

## 🛠️ Tools & Libraries

- 🐍 Python 3
- 🔗 TensorFlow 2.x / Keras
- 📊 Matplotlib
- ☁️ Google Colab (for training)

---

## 🧱 Model Architecture

- **3 Convolutional layers** (with ReLU + MaxPooling)
- **Flatten layer**
- **Dense layers with Dropout**
- **Output layer** with Softmax (10 classes)

---

## 📈 Training Summary

- **Loss function**: Sparse Categorical Crossentropy
- **Optimizer**: Adam
- **Epochs**: 10
- **Test Accuracy**: ~75–80%

---

## 🔍 Example Predictions

| Predicted | Actual |
|-----------|--------|
| 🐶 Dog    | 🐶 Dog |
| 🛳️ Ship   | 🛳️ Ship |
| 🐱 Cat    | 🐶 Dog |
| ✈️ Airplane | ✈️ Airplane |

> ✅ View the full image output in `/cifar10_predictions_clear.png`

---
