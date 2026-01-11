# LATE-ON-TIME-DELIVERY-PREDICTION_DASHBAORD-CHAIN_SUPPLY_ANALYTICS.
This project predicts telecom customer churn using machine learning. After data preprocessing and EDA, models like Logistic Regression, XGBoost, and Neural Networks were trained and evaluated using accuracy, precision, recall, F1-score, and confusion matrices to identify customers likely to leave and support retention strategies.



Project Title

Late Delivery Risk Prediction Dashboard

📖 Project Overview

This project predicts whether an order will be delivered late or on time using machine learning. It helps supply chain and logistics teams identify risky shipments early and take corrective action to reduce delays and customer dissatisfaction.

🎯 Problem Statement

Late deliveries increase logistics cost, impact customer satisfaction, and cause inventory issues.
The goal is to predict late delivery risk in advance using historical order data.

📊 Dataset Information

Rows: ~108,000

Columns: 54

Target Variable: Late_delivery_risk

0 → On Time

1 → Late

Key Features

Days for shipping (real & scheduled)

Shipping mode

Category, market, region

Sales, quantity, discount, profit

⚙️ Data Preprocessing

Handling missing values

Label encoding for categorical variables

Feature scaling using StandardScaler

Train-test split

🤖 Machine Learning Models Used

Logistic Regression

Random Forest

XGBoost

Neural Network (ANN)

📈 Model Evaluation

Models were evaluated using:

Accuracy

Precision

Recall

F1-score

Confusion Matrix

Feature Importance (tree-based models)

📊 Dashboard Features

Interactive order input sidebar

Late / On-Time predictions from 4 models

Visualizations (charts & KPIs)

Built using Streamlit

🚀 Future Improvements

Real-time data integration

Batch prediction support

Model accuracy optimization

Advanced filtering by region & category

🛠️ Tools & Technologies

Python

Pandas, NumPy

Scikit-learn

XGBoost

Streamlit

Matplotlib / Seaborn

👩‍💻 Author

Aelia Shah
BSCS (Data Science) – NED University

