# 🏦 Bank Term Deposit Prediction

This project uses supervised machine learning techniques to predict whether a customer will subscribe to a term deposit (a marketing campaign outcome) based on various client and campaign attributes.

## 📁 File Structure

- `Team Deposit prediction.ipynb`: Main Jupyter Notebook containing data analysis, preprocessing, modeling, and evaluation.

## 📊 Dataset

The dataset includes features like:
- Customer attributes (age, job, marital status, etc.)
- Contact communication details (contact type, last contact duration)
- Campaign information (number of contacts, previous outcomes)
- Economic context (employment variation rate, consumer confidence index)

> **Target Variable**: `y` — whether the client subscribed to a term deposit (yes/no)

## 🧠 ML Models Used

The notebook explores different machine learning models such as:
- Logistic Regression
- Decision Trees
- Random Forest
- XGBoost

## 🧹 Key Steps

1. **Data Preprocessing**
   - Handling missing values
   - Encoding categorical variables
   - Feature selection

2. **Model Training & Evaluation**
   - Splitting data into train/test
   - Using accuracy, precision, recall, F1-score
   - Confusion matrix and ROC-AUC

3. **Model Explanation**
   - SHAP or LIME (for model interpretability)

## 📈 Results

The project compares model performance and selects the best one based on validation scores and interpretability.

## 🚀 Getting Started

To run the notebook:

```bash
git clone https://github.com/Intzar-mahdi/Team-Deposit_prediction.git

