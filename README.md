# Task 33: Simple Linear Regression

**Track:** AI & ML Track  
**Day:** 33  

## Description
This project implements a **Simple Linear Regression** model using Scikit-Learn to predict a numerical target variable (`Salary`) based on a single continuous feature (`YearsExperience`).

---

## Objectives
* Load and pre-process the dataset (`Salary_Data.csv`).
* Split data into **80% Training** and **20% Testing** sets.
* Fit a Ordinary Least Squares Simple Linear Regression model.
* Evaluate the model performance using **Mean Squared Error (MSE)** and **R^2 Score**.
* Visualize both training and testing regression fits.

---

## Tools & Libraries
* **Python** 3.x
* **Pandas** — Data manipulation
* **NumPy** — Numerical computing
* **Matplotlib** — Data visualization
* **Scikit-learn** — Model building and metrics

---

## Model Results & Metrics

### Linear Equation Parameters:
* **Slope / Coefficient (m):** `9423.82`
* **y-Intercept (c):** `25321.58`

$$\text{Salary} = 9423.82 \times \text{YearsExperience} + 25321.58$$

### Model Performance:
* **Mean Squared Error (MSE):** `49830096.86`
* **R-squared ($R^2$) Score:** `0.9024` (Explains ~90.24% of variance)

---

## Visualizations

### 1. Training Set Results
![Training Set Plot](Screenshot%202026-11-11%20102906.png)

### 2. Test Set Results
![Test Set Plot](Screenshot%202026-11-11%20102929.png)

---

## Interview Questions & Answers

### Q1: What is Linear Regression?
**Answer:**  
Linear Regression is a fundamental supervised machine learning algorithm used to model the relationship between a continuous dependent target variable (y) and one or more independent predictor variables (X). It fits a straight line that minimizes the sum of squared residuals (differences between actual and predicted values).

### Q2: What is the dependent variable?
**Answer:**  
The dependent variable (also known as the target or response variable, denoted as y) is the continuous variable whose outcome we aim to predict based on input variables. In this project, **`Salary`** is the dependent variable.

### Q3: What does the coefficient represent?
**Answer:**  
The coefficient (slope, m) represents the expected average change in the dependent variable (y) for every one-unit change in the independent variable (x). In this dataset, a coefficient of `9423.82` means that for every additional year of experience, an employee's salary increases by approximately **$9,423.82**.
