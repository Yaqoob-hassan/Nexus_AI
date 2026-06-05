<div align="center">

# 🚀 Nexus AI — Machine Learning Internship Portfolio

[![Python](https://img.shields.io/badge/Python-3.8%2B-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)](https://jupyter.org/)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-ML-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)](https://scikit-learn.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-22c55e?style=for-the-badge)](LICENSE)

> A complete collection of AI and Machine Learning projects completed during the **Nexus AI Internship** — spanning retail analytics, predictive sales modeling, and intelligent churn detection. Each project translates raw business data into actionable, data-driven insights.

</div>

---

## 📋 Table of Contents

- [Overview](#-overview)
- [Projects](#-projects)
  - [Supermarket Sales Analysis](#-supermarket-sales-analysis)
  - [Sales Prediction](#-sales-prediction)
  - [Customer Churn Prediction](#-customer-churn-prediction)
- [Tech Stack](#-tech-stack)
- [Getting Started](#-getting-started)
- [Key Learnings](#-key-learnings)
- [Repository Structure](#-repository-structure)
- [Author](#-author)

---

## 🔍 Overview

This repository documents every project and task completed during the **Nexus AI Internship**, with a focus on building real-world AI and ML solutions using Python. The three projects cover the full spectrum of a data science workflow — from exploratory analysis to production-ready predictive models.

Every project follows a rigorous end-to-end pipeline:

```
Business Problem → Data Exploration → Preprocessing → Modeling → Evaluation → Insights
```

---

## 📁 Projects

---

### 🛒 Supermarket Sales Analysis

**Folder:** `SuperMarketSales/`

**Objective:** Perform in-depth exploratory analysis on supermarket transaction data to uncover top-performing products, peak sales periods, and revenue trends that can inform business strategy.

| Detail | Info |
|--------|------|
| **Type** | Exploratory Data Analysis (EDA) |
| **Dataset** | Supermarket Sales Dataset (transactions across branches, products & customers) |
| **Focus Areas** | Sales trends, product performance, customer behavior, branch comparison |
| **Libraries** | pandas, Matplotlib, Seaborn |

**Key Highlights:**
- Branch-level and product-line revenue breakdown to identify top performers
- Time-series analysis of daily and monthly sales patterns
- Customer demographics analysis — gender, membership type, and payment preferences
- Correlation heatmaps and distribution plots for feature understanding
- Rich, publication-quality visualizations for business storytelling

---

### 📈 Sales Prediction

**Folder:** `Sales_Prediction_Task2/`

**Objective:** Build and benchmark multiple regression models to accurately forecast future sales, enabling inventory planning and revenue projections.

| Detail | Info |
|--------|------|
| **Type** | Regression / Predictive Modeling |
| **Dataset** | Sales Dataset with advertising, product, and market features |
| **Algorithms** | Linear Regression, Decision Tree Regressor, Random Forest Regressor |
| **Metrics** | MAE, MSE, RMSE, R² Score |

**Key Highlights:**
- Feature correlation analysis to identify the strongest sales drivers
- Compared three regression models side-by-side on identical train/test splits
- Random Forest delivered the best generalization with lowest RMSE
- Residual plot analysis to diagnose model fit and heteroscedasticity
- Feature importance ranking for interpretable, actionable model outputs

---

### 📉 Customer Churn Prediction

**Folder:** `Customer_Churn_Task_3/`

**Objective:** Predict which customers are likely to churn, enabling proactive retention strategies that reduce revenue loss.

| Detail | Info |
|--------|------|
| **Type** | Binary Classification |
| **Dataset** | Telecom / Subscription Customer Dataset |
| **Algorithms** | Logistic Regression, Decision Tree Classifier, Random Forest Classifier |
| **Metrics** | Accuracy, Precision, Recall, F1-Score, Confusion Matrix |

**Key Highlights:**
- End-to-end preprocessing pipeline: missing value handling, label encoding, feature scaling
- Multi-model comparison with confusion matrix visualization for each classifier
- Anomaly detection on misclassified samples to understand model blind spots
- Identified key churn indicators: contract type, tenure, and monthly charges
- Business-focused interpretation: minimizing false negatives to protect at-risk customers

---

## 🛠 Tech Stack

| Category | Libraries / Tools |
|----------|-------------------|
| **Language** | Python 3.8+ |
| **Notebooks** | Jupyter Notebook |
| **Data Manipulation** | NumPy, pandas |
| **Visualization** | Matplotlib, Seaborn |
| **Machine Learning** | scikit-learn |
| **Version Control** | Git & GitHub |

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/Yaqoob-hassan/Nexus_AI.git
cd Nexus_AI
```

### 2. Install Dependencies

```bash
pip install numpy pandas matplotlib seaborn scikit-learn jupyter
```

### 3. Launch Jupyter Notebook

```bash
jupyter notebook
```

Navigate to any project folder and open the `.ipynb` file to explore the full analysis.

---

## 🎯 Key Learnings

The Nexus AI internship sharpened the following skills across three real-world business problems:

- **Retail Analytics** — Extracting meaningful business intelligence from transactional data
- **Predictive Modeling** — Building, comparing, and selecting regression models for forecasting
- **Churn Analysis** — Understanding customer lifecycle data and risk modeling
- **Model Diagnostics** — Using residual analysis and confusion matrices to debug models
- **Anomaly Detection** — Identifying and investigating misclassified samples
- **Business Communication** — Translating model outputs into clear, actionable insights

---

## 📂 Repository Structure

```
Nexus_AI/
│
├── SuperMarketSales/
│   └── SuperMarketSales.ipynb
│
├── Sales_Prediction_Task2/
│   └── Sales_Prediction.ipynb
│
├── Customer_Churn_Task_3/
│   └── Customer_Churn.ipynb
│
├── .gitignore
├── LICENSE
└── README.md
```

---

## 👨‍💻 Author

**Yaqoob Hassan**
AI & Machine Learning Intern @ Nexus AI | Data Science Enthusiast

[![GitHub](https://img.shields.io/badge/GitHub-Yaqoob--hassan-181717?style=flat-square&logo=github)](https://github.com/Yaqoob-hassan)

---

<div align="center">

*Built with ❤️ during the Nexus AI Machine Learning Internship*

⭐ If you find this repository helpful, please consider giving it a star!

</div>
