# **Bank Marketing Subscription Prediction**

An end-to-end machine learning project built on the **Portugal Bank Marketing Dataset**.
The goal is to predict whether a customer will subscribe to a **term deposit** based on demographic, behavioral, and campaign-related features.

---

## **📌 Project Overview**

This project covers the full data science pipeline:

* Data cleaning & preprocessing
* Handling missing values, skewness, and outliers
* Exploratory Data Analysis (EDA)
* Feature engineering & encoding
* Scaling numerical features
* Model training with multiple classifiers
* Model comparison using standard evaluation metrics
* Final insights and interpretation

---

## **📂 Dataset**

* **Source: Portugal Bank Marketing Dataset
* **Target Variable:** `y` (subscription: yes/no)
* Contains customer demographic info, marketing interaction details, and economic indicators.

---

## **🧹 Data Preprocessing**

* Handled missing values using appropriate statistical methods (median/mean).
* Treated skewed distributions and removed outliers.
* Encoded categorical features (Label/One-Hot Encoding).
* Standardized numerical columns for model stability.

---

## **📊 Exploratory Data Analysis**

Includes visual and statistical exploration of:

* Age distribution
* Job & education patterns
* Contact/communication trends
* Relationship between features and subscription outcome
* Correlations between numerical variables

(EDA done using matplotlib, seaborn, pandas.)

---

## **🤖 Models Used**

Multiple classification algorithms were trained and evaluated:

* Logistic Regression
* Decision Tree
* Random Forest
* XGBoost (if implemented)
* KNN
* SVM

---

## **📈 Evaluation Metrics**

Models were compared using:

* Accuracy
* Precision
* Recall
* F1-score
* ROC-AUC
* Confusion Matrix

The best model was selected based on balanced performance across these metrics.

---

## **🔍 Key Insights**

* Certain demographic groups and communication strategies strongly affect conversion.
* Contact duration and month/weekday patterns influence subscription likelihood.
* Balanced preprocessing improved model stability and accuracy.

---

## **🛠️ Tech Stack**

* **Python 3.x**
* **Pandas, NumPy**
* **Matplotlib, Seaborn**
* **Scikit-learn**
* **XGBoost** (optional)


## **📌 Conclusion**

This project demonstrates a complete machine learning workflow — from raw data to evaluated models — and showcases practical experience in handling real-world classification problems.

