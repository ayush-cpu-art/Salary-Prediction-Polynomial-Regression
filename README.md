# 💰 Salary Prediction using Polynomial Regression

## 📌 Overview

This project predicts employee salaries based on their position level using **Polynomial Regression**.

The project demonstrates how polynomial features can be used to model a **non-linear relationship** between an employee's position level and salary.

---

## 🎯 Objective

The main objectives of this project are to:

- Understand the relationship between position level and salary
- Preprocess and analyze the dataset
- Apply Polynomial Regression
- Evaluate model performance using regression metrics
- Visualize the fitted polynomial regression curve

---

## 📊 Dataset

**Dataset:** Position Salaries Dataset

The dataset contains information about employee positions, their corresponding levels, and salaries.

**Source:** Kaggle – Position Salaries Dataset

---

## 🛠️ Technologies & Libraries

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

---

## ⚙️ Methodology

The project follows the following workflow:

1. Load the Position Salaries dataset
2. Explore and understand the data
3. Perform data preprocessing
4. Separate input and target variables
5. Generate polynomial features
6. Train a Polynomial Regression model with **Degree = 3**
7. Generate salary predictions
8. Evaluate the model using:
   - Mean Absolute Error (MAE)
   - Mean Squared Error (MSE)
   - R² Score
9. Visualize the original data and polynomial regression curve

---

## 📈 Model

### Polynomial Regression

Polynomial features of **degree 3** are used to capture the non-linear relationship between position level and salary.

The model allows the relationship between the input variable and salary to be represented by a polynomial rather than a straight line.

---

## 📊 Results

The Polynomial Regression model captures the non-linear relationship between position level and salary.

Model performance is evaluated using:

- **MAE**
- **MSE**
- **R² Score**

The visualizations further demonstrate how the polynomial curve fits the underlying data.

> Exact metric values are available in the project notebook.

---

## 📉 Visualizations

### Original Data

![Scatter Plot](images/scatter_plot.png)

### Polynomial Regression Curve

![Polynomial Regression Curve](images/polynomial_regression_curve.png)

---

## 📂 Project Structure

```text
Salary-Prediction-Polynomial-Regression/
│
├── images/
│   ├── scatter_plot.png
│   └── polynomial_regression_curve.png
│
├── Assignment-3.ipynb
├── Position_Salaries.csv
├── README.md
└── LICENSE