# Hi, I'm Lata 👋

🎓 MSc Data Science student at University of SUssex.   
💻 Data Science | Machine Learning | Python | SQL  
📍 United Kingdom

## About Me

- 🔭 Currently working on Machine Learning and Data Science projects
- 🌱 Learning ML, NLP, Transformers & LLMs
- 📊 Interested in Fraud Detection and Explainable AI
- 🎯 Looking for Data Science / ML opportunities

## Tech Stack

Python | SQL | Pandas | NumPy | Scikit-learn | PyTorch | XGBoost | Git

## Featured Projects

### 💳 Fraudulent Customer Transaction Detection

Developed an end-to-end machine learning system to detect fraudulent customer transactions using the IEEE-CIS Fraud Detection dataset, containing over 590,000 transactions and 400+ features.

What I built

Merged transaction and identity datasets and handled large-scale preprocessing, missing values, categorical variables, and feature engineering.

Built and compared multiple supervised models:

Logistic Regression

Random Forest

XGBoost

CatBoost

Multi-Layer Perceptron (MLP)

Implemented unsupervised fraud detection approaches using:

Isolation Forest

Autoencoder

Addressed severe class imbalance using SMOTE and appropriate train/test separation to avoid data leakage.

Used PR-AUC as the primary evaluation metric, as it is more informative than accuracy for highly imbalanced fraud datasets.

Optimised classification thresholds using validation data rather than relying on the default 0.5 threshold.

Built ensemble models using Soft Voting and Stacking, with Logistic Regression as the stacking meta-model.

Evaluated model reliability using bootstrap 95% confidence intervals for PR-AUC and ROC-AUC.

Tested model performance over different transaction time periods to assess temporal stability.

Applied SHAP explainability to understand which features influenced fraud predictions across different models.

Key Achievement

The Stacking Ensemble achieved the best overall PR-AUC of 0.4792, outperforming individual models including:

XGBoost: 0.4599 PR-AUC

Random Forest: 0.4573 PR-AUC

The stacking model also achieved a ROC-AUC of 0.8882.

Production-style Web Application

Built a full-stack fraud monitoring application using Flask, Jinja2 and JavaScript.

The application includes:

Real-time transaction monitoring

Chronological replay of test transactions using Server-Sent Events (SSE)

Automatic fraud scoring for incoming transactions

Manual transaction testing

Fraud analytics dashboard

Model explainability using SHAP

REST-style API demonstration

The application was containerised and deployed to Google Cloud Run, turning the machine learning project into a working end-to-end fraud detection system rather than only a notebook-based experiment.

### 📉 Customer Churn Prediction
Machine learning project for predicting customer churn.

### 🌪 Hurricane Forecasting
7-day weather forecasting using PyTorch neural networks.

## Connect with me

LinkedIn: (https://www.linkedin.com/in/lata-bharati-04575a1a0/)
