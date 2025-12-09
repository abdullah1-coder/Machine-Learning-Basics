# 📈 Machine Learning Basics: Linear Regression Projects

This repository contains foundational Machine Learning projects exploring **Supervised Learning** algorithms. It focuses on **Simple Linear Regression** and **Multiple Linear Regression** to solve predictive modeling problems using Python and Scikit-Learn.

## 🧠 Overview

The goal of this repository is to demonstrate a clear understanding of the mathematical foundations of regression analysis, data preprocessing, model training, and evaluation.

### 🛠️ Tech Stack
* **Python** (Core Logic)
* **Scikit-Learn** (Model Training & Evaluation)
* **Pandas & NumPy** (Data Manipulation)
* **Matplotlib & Seaborn** (Data Visualization & Correlation Heatmaps)

---

## 📂 Project 1: Student Score Prediction (Simple Linear Regression)
**File:** `Simple_Regression_Analysis.ipynb`

### 🎯 Objective
To predict a student's percentage score based on the number of hours they study.

### 🔑 Key Steps
1.  **Exploratory Data Analysis (EDA):** Visualized the relationship between `Hours` and `Scores` using scatter plots.
2.  **Model Training:** Built a Simple Linear Regression model (`y = mx + b`) to find the line of best fit.
3.  **Prediction:** Created a script where users can input study hours to generate a predicted score instantly.

---

## 📂 Project 2: Employee Salary Prediction (Multiple Linear Regression)
**File:** `Multiple_Linear_Regression.ipynb`

### 🎯 Objective
To predict an employee's salary based on multiple features: Total Experience, Team Lead Experience, Project Manager Experience, and Certifications.

### 🔑 Key Steps
1.  **Correlation Analysis:** Used a **Seaborn Heatmap** to identify which features had the strongest impact on salary.
    * *Insight:* Experience variables showed a much higher correlation with salary than certifications.
2.  **Model Training:** Trained a Multiple Linear Regression model on 80% of the dataset.
3.  **Coefficient Interpretation:** Analyzed the model's coefficients to understand the monetary value assigned to different types of experience.
    * *Example:* The model assigned a specific dollar value increase for every additional year of "Team Lead" experience vs. standard experience.
4.  **Evaluation:** Achieved an **R² Score of ~94%**, indicating the model explains 94% of the variance in salary data.

---

## 📊 Visualizations

The projects include:
* **Regression Lines** to visualize the fit of the model against actual data.
* **Correlation Heatmaps** to detect multicollinearity and feature importance.

## 🚀 How to Run

1.  Clone this repository:
    ```bash
    git clone [https://github.com/yourusername/Machine-Learning-Basics.git](https://github.com/yourusername/Machine-Learning-Basics.git)
    ```
2.  Install the required libraries:
    ```bash
    pip install pandas numpy matplotlib seaborn scikit-learn
    ```
3.  Open the notebooks in Jupyter or Google Colab to run the models.

## 🔮 Future Improvements
* Implementing **Polynomial Regression** for non-linear data.
* Adding **Lasso and Ridge Regression** to handle overfitting.

---

*Created by Abdullah-Bin-Shahbaz – Documenting my journey into Data Science & AI.*
