# Auto Model Selection for Linear Regression

## Overview

This project automatically selects the **best linear regression model** by trying different **polynomial degrees** and choosing the one with the **lowest cross‑validation (CV) error**.

---

## What the Code Does

* Tries polynomial degrees from **1 to 10**
* Scales features using **StandardScaler**
* Trains a **Linear Regression** model for each degree
* Computes **Training MSE** and **CV MSE**
* Selects the model with **minimum CV MSE**

---

## Why This Is Used

* To avoid **underfitting and overfitting**
* To find the right model complexity automatically
* To understand the **bias–variance trade‑off**

---

## Output

* A plot of **Polynomial Degree vs MSE**
* Best model is the one with **lowest CV error**

---

## Tools Used

* Python
* scikit‑learn
* NumPy
* Matplotlib
