# Churn Prediction Project

## Overview
This project focuses on predicting customer churn for an internet subscription service using machine learning models. We use a dataset retrieved from [HuggingFace](https://huggingface.co/datasets/d0r1h/customer_churn), and perform data cleaning, analysis, and model training to forecast the likelihood of customers unsubscribing.

## Key Features:
- **Data Processing:** Cleaning and handling missing values and outliers.
- **Feature Engineering:** Creation of new features such as `month_joining_date` and `last_visit_time`.
- **Model Training:** Comparison of multiple machine learning models including Logistic Regression, Random Forest, Decision Trees, Gradient Boosted Trees, etc.
- **Performance Evaluation:** Models were evaluated using metrics such as Accuracy, Precision, Recall, F1-score, and ROC AUC.

## Tools and Libraries:
- **PySpark:** For big data processing and model training.
- **Pandas & NumPy:** For data manipulation.
- **Matplotlib & Seaborn:** For data visualization.
- **scikit-learn:** For machine learning algorithms.

## Models Used:
We experimented with six different machine learning models:
- Logistic Regression
- Random Forest
- Gradient Boosted Trees
- Decision Tree
- Naive Bayes
- Linear SVC

The best-performing model was **Gradient Boosted Trees**, achieving an F1-score of 93.9%.

## Installation:
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/churn-prediction.git
   ```
2. Install the required dependencies
    ```bash
   pip install -r requirements.txt
   ```
