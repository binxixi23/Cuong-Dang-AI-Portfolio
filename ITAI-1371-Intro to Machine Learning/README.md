# Intro to Machine Learning (ITAI 1371)

## Course Overview
This directory contains my engineering laboratories, theoretical research journals, and analytical projects completed during my studies in the Applied AI and Robotics program. The coursework covers the entire end-to-end machine learning lifecycle: tooling configuration, exploratory data analysis (EDA), data preparation pipelines, feature engineering, classic supervised algorithms (regression and classification), model validation matrices, and regularization methods.

---

## Core Projects & Laboratory Index

### 1. Midterm Project: Telco Customer Churn EDA
* **Directory**: [./Midterm/](./Midterm/)
* **Problem Statement**: Telecommunications subscriber retention requires analyzing customer telemetry to pinpoint specific billing cycles, service configurations, or pricing structures that catalyze customer attrition.
* **Approach**:
  * Cleaned messy datatypes (e.g., mapped `TotalCharges` to float types) and handled unrecorded data points.
  * Computed data profile attributes and constructed correlation matrices.
  * Formulated exploratory data visualizations before and after preprocessing routines.
* **Key Findings**: Month-to-month contracting structures and high monthly charge baselines correlated with increased churn risk.

### 2. Machine Learning Lifecycle Laboratories
* **[Module 01](./Module%2001%20Welcome%20Intro%20and%20What%20is%20Machine%20Learning/) & [Module 02](./Module%2002%20Tools%20Used%20in%20Machine%20Learning/)**: Environment Setup & Infrastructure
  * Configured local Git structures, mapped cloud repositories, and established reproducible execution environments using Google Colab and Jupyter Notebooks.
* **[Module 03](./Module%2003%20ML%20Workflow%20and%20Types%20Learning/) & [Module 04](./Module%2004%20Working%20with%20Data%20%26%20EDA/)**: Data Pipelines & Exploratory Engineering
  * Blueprinted core machine learning ingestion workflows and built structured scripts for profiling distributions, missing values, and visual statistical properties.
* **[Module 05](./Module%2005%20Data%20Preparation%20%26%20Feature%20Engineering/)**: Feature Engineering & Preprocessing
  * Built functional scaling, normalization, and categorical encoding pipelines. Cleaned raw structural spaces into model-ready structures.
* **[Module 06](./Module%2006%20Regression%20%26%20Classification/)**: Algorithm Deployment
  * Implemented classic supervised regression and classification models using scikit-learn.
* **[Module 07](./Module%2007%20Evaluating%20Machine%20Learning%20Models/) & [Module 08](./Module%2008%20Overfitting%20Underfitting%20Regularization/)**: Validation & Regularization Optimization
  * Constructed model validation scoreboards including confusion matrices, precision/recall curves, and ROC curves. Fixed overfit models by applying L1/L2 regularization and addressing bias-variance trade-offs.

---

## Technical Arsenal
* **Languages**: Python (3.x)
* **Core Libraries**: Pandas, NumPy, Scikit-Learn
* **Visualization Tools**: Matplotlib, Seaborn
* **Metrics Used**: Accuracy, Precision, Recall, F1-Score, R-squared ($R^2$), Mean Squared Error (MSE)

---

## How to Execute the Notebooks
1. Ensure your workspace includes standard dependencies: `pip install numpy pandas scikit-learn matplotlib seaborn`.
2. Navigate into the targeted module or project folder.
3. Open the `.ipynb` notebook file inside Google Colab or a local Jupyter server environment.
4. *Note: All notebooks have been pre-run with cached cell outputs fully visible directly on GitHub for portfolio review.*
