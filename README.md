# Credit Scoring Model 📊

A machine learning project to predict creditworthiness and loan default risk based on historical financial data. This project demonstrates a complete data science workflow, from data cleaning and feature engineering to model training, evaluation, and visualization.

---

## 🚀 Objective

The primary goal of this project is to build and evaluate a classification model that accurately predicts whether an individual is likely to default on a loan. This helps financial institutions make informed, data-driven lending decisions.

---

## ✨ Key Features

* **Data Cleaning**: Handles missing values in the dataset using median imputation.
* **Feature Engineering**: Creates a new, insightful feature (`debt_to_income_ratio`) to enhance model performance.
* **Model Training**: Implements and trains three distinct classification algorithms:
    * Logistic Regression
    * Decision Tree
    * Random Forest
* **Comprehensive Evaluation**: Assesses models using standard metrics like Precision, Recall, F1-Score, and ROC-AUC.
* **Visual Analysis**: Generates a comparative ROC curve plot to visually determine the most effective model.

---

## 💾 Dataset

This project uses the `credit_risk_dataset.csv`, which contains anonymized financial and personal data for over 32,000 loan applicants.

**Key columns include:**
* `person_age`, `person_income`, `person_home_ownership`
* `loan_intent`, `loan_grade`, `loan_amnt`, `loan_int_rate`
* `cb_person_default_on_file`, `cb_person_cred_hist_length`
* `loan_status` (Target Variable: `1` for default, `0` for non-default)

---

## 🛠️ Setup and Installation

To run this project, you'll need Python 3 and a few common data science libraries.

1.  **Clone the repository or download the files.**

2.  **Install the required libraries:**
    ```bash
    pip install pandas scikit-learn matplotlib
    ```

---

## ▶️ How to Run

Ensure the `credit_risk_dataset.csv` file is in the same directory as the Python script. Then, simply execute the main script from your terminal:

```bash
python credit_scoring_model.py
