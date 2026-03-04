UCS761-Deep Learning 
Saniya Jindal
(102303183)
# UCS761: Deep Learning Laboratory Solutions 🧠

This repository contains scratch-level implementations of Deep Learning concepts, starting from basic Linear Regression to advanced Vision Models (CNNs), developed as part of the **UCS761** course.

## 🚀 Project Overview
The goal of this lab series is to build and understand neural networks using only **NumPy** and **Pandas**, without relying on high-level libraries like PyTorch or TensorFlow.

---

## 📂 Lab Modules

### 📍 Lab 4: Multiple Linear Regression
- **Objective:** Predicting numeric values (Salary) using a single linear neuron.
- **Key Concepts:** Mean Squared Error (MSE), Gradient Descent, Feature handling.
- **Tools:** Python, NumPy, Pandas.

### 📍 Lab 5: Linear Estimation (Abalone Dataset)
- **Objective:** Predicting the age of Abalone using physical measurements.
- **Key Concepts:** Data Normalization ($Z$-score), Train-Test Split (80/20), systematic bias analysis.
- **Dataset:** UCI Abalone Dataset.

### 📍 Lab 6: Learning to Bend (Non-Linear Regression)
- **Objective:** Breaking the "linear" barrier by introducing hidden layers.
- **Key Features:** - Implementation of **ReLU Activation**.
  - 2-Layer Neural Network ($1 \to 10 \to 1$).
  - Manual Backpropagation using the **Chain Rule**.

### 📍 Lab 7: From Neurons to Vision Models
- **Objective:** Building a complete pipeline for Digit Classification (MNIST).
- **Experiments:**
  - **Dense vs. CNN:** Analysis of spatial hierarchy and parameter sharing.
  - **Vanishing Gradient:** Comparison between **Sigmoid** and **ReLU** using Gradient Norms.
  - **Optimizers:** Manual implementation of SGD.
- **Data Splitting:** 70% Train, 15% Validation, 15% Test.

---

## 📊 Key Visualizations
Each lab includes plots to verify learning:
* **Loss Curves:** Tracking the reduction of MSE/Cross-Entropy.
* **Regression Lines:** Visualizing the "bend" in non-linear models.
* **Gradient Norms:** Monitoring signal stability across deep layers.

---

## 🛠️ Tech Stack
* **Language:** Python 3.x
* **Libraries:** NumPy, Pandas, Matplotlib
* **Environment:** Google Colab / Jupyter Notebook

---

## 📝 How to Run
1. Clone the repository:
   ```bash
   git clone [https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git](https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git)
