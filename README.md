# Gradient Descent From Scratch

## 📌 Project Overview

This project demonstrates the implementation of **Gradient Descent** from scratch for Linear Regression without using any machine learning libraries.

Using a dataset generated with Scikit-Learn's `make_regression`, the notebook shows how model parameters (**slope** and **intercept**) are updated iteratively to minimize the **Mean Squared Error (MSE)** loss function. The project focuses on building a strong mathematical and intuitive understanding of optimization in Machine Learning.

---

## 🎯 Objectives

* Understand the mathematics behind Gradient Descent
* Implement parameter optimization from scratch
* Learn how loss decreases during training
* Visualize convergence through loss curves
* Study the effect of learning rates on model training

---

## 📂 Dataset

**Dataset Used:** `make_regression`

A synthetic regression dataset generated using Scikit-Learn to demonstrate Gradient Descent and parameter optimization.

---

## 📖 Concepts Covered

* Linear Regression
* Gradient Descent
* Mean Squared Error (MSE)
* Cost Function
* Learning Rate
* Parameter Optimization
* Convergence
* Model Training

---

## 🛠️ Libraries Used

* Python
* NumPy
* Pandas
* Matplotlib

---

## ⚙️ Implementation Steps

### Data Preparation

* Generate regression data using `make_regression`
* Visualize the dataset

### Parameter Initialization

* Initialize slope (m) and intercept (b)
* Set learning rate and iterations

### Gradient Calculation

* Compute predictions
* Calculate MSE loss
* Compute gradients for m and b

### Parameter Updates

* Update parameters iteratively
* Minimize the loss function using Gradient Descent

### Visualization

* Plot Loss vs Iterations
* Visualize convergence behavior
* Display final regression line

---

## 🔍 Key Observations

* Loss decreases as Gradient Descent progresses.
* Learning rate plays a crucial role in convergence.
* Proper parameter updates lead to the optimal regression line.
* Gradient Descent forms the foundation of many ML and Deep Learning algorithms.

---

## ✅ Advantages

* Builds strong intuition for optimization algorithms
* Helps understand how machine learning models learn
* Demonstrates the role of gradients and learning rates
* Provides a foundation for advanced optimization techniques

---

## 💻 Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib

---

## 🏁 Conclusion

Gradient Descent is one of the most important optimization algorithms in Machine Learning. By implementing it from scratch, this project provides a clear understanding of how models iteratively learn the best parameters by minimizing prediction error.


