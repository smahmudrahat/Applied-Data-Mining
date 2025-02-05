
# Loan Approval Prediction

## Overview

This project is part of **ADS-502 Data Mining** and aims to predict loan approval status using machine learning techniques. Loan distribution is a core part of banking operations, and financial institutions need an efficient way to assess applicants' eligibility. This project automates the loan approval process using predictive analytics.

## Motivation

Banks rely heavily on loan distribution for revenue, yet the approval process remains lengthy and uncertain. This project introduces a **machine learning-based Loan Prediction System** to improve decision-making, reduce risks, and streamline loan processing.

## Problem Statement

The objective is to create a **Loan Prediction System** that helps banks quickly assess applicants' creditworthiness. The system automates feature validation and weighs the most relevant attributes to make accurate predictions. It benefits bank employees and applicants by providing an **efficient and transparent loan approval process**.

## Objectives

- Extract meaningful patterns from historical loan approval datasets.
- Build machine learning models to predict potential loan defaulters.
- Identify the most relevant factors influencing loan approval.
- Improve accuracy using multiple classification algorithms.

## Dataset Specifications

- The dataset was collected from online sources.
- The dataset consists of various attributes like applicant details, loan amount, credit history, etc.
- Feature selection and engineering were performed to enhance model performance.

## Machine Learning Models Used

- **Logistic Regression**
- **Decision Tree Classifier (C5.0)**
- **Random Forest Model**
- **XGBoost**
- **Naïve Bayes Classifier**

## Evaluation Metrics

- **Stratified k-folds cross-validation**
- **Accuracy**
- **ROC Curve & AUC Score**
- **Feature Importance Analysis**

## Experimental Results

- Feature importance was analyzed to determine the most influential factors.
- ROC curves were used to compare model performances.
- The best-performing model was selected based on accuracy and AUC scores.

## Installation

To set up and run this project, install the necessary dependencies:

```bash
pip install numpy pandas scikit-learn xgboost matplotlib seaborn
```

## Usage

Run the Jupyter Notebook to explore the analysis and predictions:

```bash
jupyter notebook ads_502_final_project_complete_version.ipynb
```

## Contributors

- **Kaustav Ghosh Dastidar**
- **SM Sultan Mahmud Rahat**
- **Amy Ou**

## License

This project is licensed under the **MIT License**.

---

You can upload this `README.md` to your GitHub repository. Let me know if you'd like any modifications! 🚀
