# 🧠 PyTorch Practice Repository

This repository contains my hands-on learning and implementation of PyTorch concepts, starting from the basics to building and training neural networks.

---

## 📌 Overview

The goal of this repository is to build a strong foundation in PyTorch by implementing core concepts step-by-step and applying them to real datasets like Fashion MNIST.

---

## 🚀 Topics Covered

* Tensor operations and basics
* PyTorch workflow and pipeline
* Dataset and DataLoader usage
* Training and evaluation pipeline
* Artificial Neural Networks (ANN)
* GPU acceleration with PyTorch

---

## 📂 Project Structure

```
pytorch/
│
├── tensors_in_pytorch.ipynb
├── dataset_and_dataloader_demo.ipynb
├── pytorch_training_pipeline.ipynb
├── pytorch_nn_module.ipynb
├── ann_fashion_mnist_pytorch.ipynb
├── ann_fashion_mnist_pytorch_gpu.ipynb
```

---

## 🧪 Key Implementations

### 🔹 Tensor Fundamentals

Understanding tensor creation, operations, and broadcasting in PyTorch.

### 🔹 Data Handling

Efficient data loading using `Dataset` and `DataLoader`.

### 🔹 Training Pipeline

Building a complete deep learning pipeline including:

* Forward pass
* Loss computation
* Backpropagation
* Optimization

### 🔹 Neural Network (ANN)

Implemented a fully connected neural network on the Fashion MNIST dataset.

### 🔹 GPU Training

Optimized training using CUDA for faster computation.

---

## 📊 Results & Observations

### 🖥️ CPU Training (Small Dataset)

* Trained on **5,000 samples**
* Achieved **~83% accuracy**
* Faster experimentation but limited performance due to less data

---

### ⚡ GPU Training (Full Dataset)

* Trained on **60,000 samples**
* **Training Accuracy:** ~98%
* **Test Accuracy:** ~89%
* Significant improvement due to:

  * More data
  * Faster computation
  * Better generalization

---

### 🧠 Regularization & Optimization

Applied:

* L2 Regularization
* Dropout
* Batch Normalization

**Results:**

* **Training Accuracy:** ~93%
* **Test Accuracy:** ~88%

📌 Insight:

* Reduced gap between training and test accuracy
* Successfully **reduced overfitting**
* Slight drop in training accuracy but improved model generalization

---

## 🛠️ Tech Stack

* Python
* PyTorch
* Google Colab

---

## 📈 Future Improvements

* Add CNN implementations
* Hyperparameter tuning
* Model evaluation metrics visualization
* Deploy models



