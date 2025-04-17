# ❤️ Heart Disease Prediction Project

This project focuses on predicting the likelihood of heart disease in patients using supervised machine learning algorithms. The goal is to use historical health data to build models that can accurately predict whether an individual is at risk of heart disease.

---

## 📁 Dataset

The dataset used is `heart_disease_data.csv`, containing 303 patient records with 14 features related to medical diagnostics.

### Features:
Contains basic health indicators like age, sex, cholesterol, blood pressure, etc.

---

## 📊 Exploratory Data Analysis (EDA)

- Checked class balance of the target variable
- Visualized age and sex distribution against heart disease
- Analyzed correlations among features using a heatmap
- Verified that there were no missing values

---

## 🧪 Model Building & Evaluation

### Preprocessing:
- Features standardized using `StandardScaler`
- Data split into training and testing sets (80/20) with stratification

## 🔧 Technologies Used

- Python 🐍
- Pandas & NumPy for data handling
- Seaborn & Matplotlib for visualization
- Scikit-learn for ML models and evaluation
- XGBoost for boosting performance
- GridSearchCV for hyperparameter tuning

### Evaluation Metrics:
- Accuracy
- Precision, Recall, and F1-score
- Confusion Matrix
- ROC AUC Score and ROC Curves

---

## 📈 Results Summary

| Model                  | Test Accuracy |
|------------------------|---------------|
| Logistic Regression    | **80.33**     |
| K-Nearest Neighbors    | 73.77%        |
| Support Vector Machine | **80.33**        |
| Random Forest          | 78.69%        |
| XGBoost                | 77.05%        |

### Cross-Validation Scores (Mean ± Std Dev):

- **Logistic Regression**: 83.15% ± 5.13%
- **Random Forest**: 83.82% ± 2.88%
- **KNN**: 67.02% ± 4.84%
- **SVM**: 69.98% ± 2.02%
- **XGBoost**: 78.21% ± 4.25%

---

## 📉 ROC Curves

ROC curves were plotted for all models that support probability predictions to visualize model performance across thresholds.

