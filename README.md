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


### 📈 Radar Chart Comparison

![Radar Chart]([radar_chart.png](https://github.com/RishabhYadav1202/Heart-Disease-Prediction/blob/main/Images/Radar%20Chart%20for%20Comparison.png?raw=true)
---

## 📌 Results & Insights

- Logistic Regression and SVM performed the best with ~80% accuracy.
- KNN lagged slightly behind, possibly due to sensitivity to scaling and outliers.
- Random Forest and XGBoost offered solid performance with ensemble robustness.

---

## 📎 Future Work

- Integrate SHAP/LIME for model interpretability
- Deploy the model via Streamlit or Flask
- Include real-time prediction using user input
- Perform feature importance ranking

---

## 🙌 Acknowledgements

- UCI Heart Disease dataset
- scikit-learn and XGBoost documentation
- Krish Naik's ML Bootcamp for foundational understanding

