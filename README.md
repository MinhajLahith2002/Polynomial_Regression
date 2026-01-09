# Polynomial Regression Demo 🎢

This repository contains a simple experiment with **Polynomial Regression** using Python, NumPy, Matplotlib, and scikit-learn.  
The goal is to show how different regression models (linear, quadratic, cubic, high-degree) fit data that follows a curvy relationship.

---

## 📌 Project Overview
We generate synthetic data using a polynomial formula with added noise:



\[
y = x + 1.5x^2 + 0.8x^3 + \text{noise}
\]



- **x** → Random input values (normally distributed).
- **y** → Outputs created from a polynomial function plus random noise.
- The data is split into **training**, **validation**, and **test sets**.
- Models of different polynomial degrees are trained and compared.

---

## 🛠️ Technologies Used
- **Python 3**
- **NumPy** → for data generation and manipulation
- **Matplotlib** → for visualization
- **scikit-learn** → for regression models and polynomial feature expansion

---

## 📂 Workflow
1. **Data Generation**
   - Create random `x` values.
   - Build `y` using polynomial terms and noise.

2. **Data Splitting**
   - Training set (60%)
   - Validation set (20%)
   - Test set (20%)

3. **Model Training**
   - Linear Regression (degree 1)
   - Polynomial Regression (degree 2, 3, and 20)

4. **Evaluation**
   - Compare R² scores on training, validation, and test sets.
   - Visualize fits with scatter plots.

---

## 📊 Results
- **Degree 1 (Linear)** → Underfits, poor performance.
- **Degree 2 (Quadratic)** → Better, but still misses the cubic shape.
- **Degree 3 (Cubic)** → Best fit, matches the true data-generating process.
- **Degree 20 (High-degree)** → Overfits, memorizes training data but fails on validation/test.

---

