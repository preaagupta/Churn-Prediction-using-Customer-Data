📊 Churn-Prediction-using-Customer-Data

# 📊 Churn Prediction Using Telco Customer Data

This project analyzes Telco customer data to predict whether a customer will churn (leave the service) using machine learning models. The project includes data preprocessing, exploratory data analysis (EDA), feature engineering, model training, and evaluation.

---

## 🗂️ Contents

- `churn_prediction.ipynb`: Jupyter Notebook with all the code and analysis.
- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Logistic Regression & Random Forest classification
- Model evaluation using confusion matrix and ROC curve
- Feature importance analysis

---

## 🔍 Key Steps

1. **Data Preprocessing**:
   - Handle missing values in `TotalCharges`
   - Convert data types
   - Encode target variable `Churn` into binary format

2. **EDA (Exploratory Data Analysis)**:
   - Churn distribution
   - Correlation heatmap
   - Boxplots and feature comparison

3. **Feature Engineering**:
   - One-hot encoding for categorical variables

4. **Model Building**:
   - Logistic Regression
   - Random Forest Classifier

5. **Evaluation**:
   - Confusion Matrix
   - ROC Curve
   - Feature Importance plot

---

## 📦 Libraries Used

```python
pandas
numpy
matplotlib
seaborn
scikit-learn
