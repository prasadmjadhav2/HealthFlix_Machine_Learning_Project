# 🩺 HealthFlix ML Project: Revolutionizing Patient Care with Predictive Intelligence

This repository contains the code and resources for the HealthFlix ML project, a healthcare analytics platform designed to predict medical conditions, hospital admission types, and billing estimates using real-world patient data and Artificial Intelligence.

## 📊 Dataset Overview

The analysis is based on a dataset comprising:

* **55,500 patient records**
* **15+ features** including:
    * Demographics (age, gender)
    * Medical Information (blood type, medical history, medications, test results)
    * Logistical Details (hospital & insurance information)
    * Financial Data (billing information)

## 🚀 Key ML Use Cases & Achievements

This project tackles several critical prediction tasks within the healthcare domain:

### 1️⃣ Medical Condition Prediction

* **Objective:** Predict the primary medical condition of a patient (e.g., Cancer, Obesity, Hypertension).
* **Models Used:** LightGBM & Random Forest Classifier.
* **Techniques:** Addressed class imbalance using Synthetic Minority Over-sampling Technique (SMOTE).
* **Performance:** Achieved approximately **28% accuracy** on a multi-class classification problem with 6 distinct condition categories.

### 2️⃣ Admission Type Classification

* **Objective:** Classify the type of hospital admission (Emergency, Urgent, or Elective).
* **Models Used:** Random Forest & XGBoost Classifier.
* **Techniques:** Employed GridSearchCV for hyperparameter tuning on XGBoost to enhance performance. Feature importance analysis highlighted billing amount, age, and test results as key predictors.
* **Performance:** Reached approximately **43% accuracy**.

### 3️⃣ Billing Amount Prediction (Regression)

* **Objective:** Estimate the total billing amount for a patient's hospital stay.
* **Models Used:** Random Forest Regressor & XGBoost Regressor.
* **Performance:**
    * Mean Absolute Error (MAE): ~ ₹12,408
    * Root Mean Squared Error (RMSE): ~ ₹14,321
* **Application:** Provides hospitals with valuable billing estimates before patient discharge, aiding financial planning.

### 4️⃣ End-to-End Deployment Ready Tool

* **Functionality:** Developed a tool allowing real-time predictions based on user input of patient details.
* **Outputs:** Predicts Admission Type and Estimated Billing Amount.
* **Optimization:** Utilized model ensembling (VotingClassifier for classification tasks, averaging for regression) to potentially improve robustness and accuracy.

## 📌 Tools & Techniques Used

* **Data Manipulation & Analysis:** Pandas, NumPy
* **Data Visualization:** Seaborn, Matplotlib
* **Machine Learning Algorithms:** XGBoost, LightGBM, Random Forest, Gradient Boosting
* **Data Preprocessing:** SMOTE (for imbalanced data), Label Encoding
* **Model Evaluation & Tuning:** GridSearchCV, Feature Importance Analysis

## 💡 Real-World Impact

The HealthFlix ML project aims to:

* **Streamline Hospital Workflows:** By preemptively identifying potential admission types and required care levels.
* **Optimize Financial Planning:** Through accurate prediction of healthcare costs.
* **Empower Decision-Making:** Providing physicians, administrators, and insurers with AI-backed insights.

This project demonstrates the potential of predictive modeling to bridge the gap between healthcare data and actionable intelligence, ultimately improving patient outcomes and operational efficiency.

## 📞 Connect

Let’s connect if you’re exploring AI in healthcare, insurance tech, or predictive modeling!

---

#MachineLearning #HealthcareAI #HealthTech #XGBoost #LightGBM #PredictiveAnalytics #DataScience #AI #BillingPrediction #MedicalClassification #HealthFlix #ProjectCompletion
