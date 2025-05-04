🩺 HealthFlix ML Project: Revolutionizing Patient Care with Predictive Intelligence 🩺

This repository showcases a comprehensive healthcare analytics platform developed for HealthFlix, designed to predict medical conditions, hospital admission types, and billing estimates using machine learning and real-world patient data.

📊 Dataset Overview:

Size: 55,500 patient records

Features: 15+ features, including age, gender, blood type, medical history, medications, test results, hospital & insurance details, and billing information.

🚀 Key ML Use Cases & Achievements:

1️⃣ Medical Condition Prediction

Models: LightGBM & Random Forest Classifier

Objective: To predict medical conditions such as Cancer, Obesity, and Hypertension.

Technique: Balanced class distribution using SMOTE.

Achievement: Achieved ~28% accuracy (multi-class, 6 categories).

2️⃣ Admission Type Classification

Models: Random Forest & XGBoost Classifier

Objective: To predict whether a case is Emergency, Urgent, or Elective.

Technique: Enhanced accuracy via grid-tuned XGBoost.

Achievement: Achieved ~43% accuracy. Feature importance analysis highlighted billing amount, age, and test results as key predictors.

3️⃣ Billing Amount Prediction (Regression)

Models: Random Forest and XGBoost Regressors

Objective: To provide hospitals with estimated billing amounts before patient discharge.

Achievement: Achieved MAE ~ ₹12,408 and RMSE ~ ₹14,321.

4️⃣ End-to-End Deployment Ready

Feature: Developed a real-time input-based prediction tool.

Functionality: Users can input patient details and receive predictions for:

Admission Type

Estimated Billing Amount

Optimization: Trained models were optimized and ensembled (VotingClassifier for classification, averaging for regression).

📌 Tools & Techniques Used:

Python

Pandas, NumPy, Seaborn, Matplotlib

XGBoost, LightGBM, Random Forest, Gradient Boosting

SMOTE for imbalanced data

Label Encoding, GridSearchCV, Feature Importance Analysis

💡 Real-World Impact:

This project aims to:

Streamline hospital workflows by preemptively identifying treatment types.

Optimize financial planning with accurate cost predictions.

Empower physicians and insurers through AI-backed decision support.

🚀 Next Steps (Optional):

Explore other advanced regression and classification techniques.

Gather more data to improve model performance.

Deploy the model as a web application.

🤝 Let's Connect!

I'm passionate about exploring the intersection of AI and healthcare. Feel free to connect if you're interested in discussing AI in healthcare, insurance tech, or predictive modeling!
