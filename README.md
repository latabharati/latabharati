# Hi, I'm Lata

🎓 MSc Data Science student at the **University of Sussex**  
💻 Data Science | Machine Learning | Python | SQL  
📍 United Kingdom  

## 👩‍💻 About Me

- 🔭 Currently working on **Machine Learning and Data Science projects**
- 🌱 Learning **Machine Learning, NLP, Transformers and LLMs**
- 🚀 Interested in building end-to-end ML solutions, from data preprocessing to deployment
- 🎯 Looking for **Data Science / Machine Learning opportunities**

---

## 🛠 Tech Stack

**Languages:**  
Python | SQL | JavaScript

**Data Science & Machine Learning:**  
Pandas | NumPy | Scikit-learn | PyTorch | XGBoost | CatBoost | SHAP | SMOTE

**Development & Deployment:**  
Flask | Jinja2 | HTML | CSS | JavaScript | Git | Google Cloud Run

---

# 🚀 Featured Projects

## 1. 💳 Fraudulent Customer Transaction Detection https://github.com/latabharati/project-fraudshield

Developed an **end-to-end machine learning fraud detection system** using the **IEEE-CIS Fraud Detection dataset**, containing more than **590,000 transactions and 400+ features**.

The project focused not only on building predictive models, but also on handling real-world challenges such as **high-dimensional data, severe class imbalance, model explainability, threshold optimisation and deployment**.

### 🔍 Data Processing & Feature Engineering

- Merged large **transaction and identity datasets**
- Processed more than **590,000 transaction records**
- Worked with **400+ numerical and categorical features**
- Handled missing values and high-dimensional data
- Performed categorical encoding and numerical preprocessing
- Created additional time-related features for transaction analysis
- Used **StandardScaler** where appropriate
- Applied **SMOTE only on training data** to prevent data leakage

### 🤖 Machine Learning Models

- Supervised: Logistic Regression, Random Forest, XGBoost, CatBoost, Multi-Layer Perceptron (MLP)
- Unsupervised: Isolation Forest, Autoencoder
- Ensemble Learning: Soft Voting, Stacking
The stacking model used predictions from multiple base models with **Logistic Regression as the meta-model**.

### 📊 Model Evaluation

Because fraudulent transactions represent only a small percentage of the dataset, traditional accuracy was not sufficient. The models were therefore evaluated using:

- **PR-AUC**
- ROC-AUC
- Precision
- Recall
- F1-score
- Confusion Matrix

Classification thresholds were selected using validation data rather than relying on the default **0.5 probability threshold**.

### 🏆 Key Results

The **Stacking Ensemble achieved the strongest overall performance**:

- **Stacking Ensemble PR-AUC: 0.4792**
- **XGBoost PR-AUC: 0.4599**
- **Random Forest PR-AUC: 0.4573**
- **Stacking ROC-AUC: 0.8882**

I also used **bootstrap resampling** to calculate **95% confidence intervals** for PR-AUC and ROC-AUC.

Model performance was evaluated across different transaction time periods to investigate **temporal stability**.

### 🔎 Explainable AI

Implemented **SHAP (SHapley Additive exPlanations)** to understand how different features influenced fraud predictions.

This allowed the system to provide insight into:

- Important fraud indicators
- Feature contributions
- Reasons behind individual model predictions

---

## 🌐 Fraud Detection Web Application

To take the project beyond a Jupyter Notebook, I built a **full-stack fraud monitoring web application**.

The application was developed using:

**Flask | Jinja2 | HTML | CSS | JavaScript**

### Web Application Features

- 📡 **Real-time transaction monitoring**
- 🔄 Chronological transaction replay using **Server-Sent Events (SSE)**
- 🤖 Automatic machine learning fraud scoring
- 🧪 Manual transaction testing
- 📊 Interactive fraud analytics dashboard
- 🔎 SHAP-based model explainability
- 📈 Fraud probability and model prediction display
- 🔌 REST-style API demonstration

Transactions from the test dataset can be replayed chronologically through the application, simulating a **live transaction monitoring environment**.

Each transaction is automatically passed through the trained ML pipeline and classified as potentially **fraudulent or legitimate**.

### ☁️ Deployment

The application was:

- Containerised for deployment
- Configured with the trained machine learning pipeline
- Deployed to **Google Cloud Run**

This transformed the project from a machine learning experiment into a **working end-to-end fraud detection system covering data processing, modelling, explainability, real-time monitoring and cloud deployment**.

---

## 2. 📉 Customer Churn Prediction

Built a machine learning system to predict customers who are likely to leave a service.

Key areas explored:

- Exploratory Data Analysis
- Data preprocessing
- Feature engineering
- Class imbalance
- Classification models
- Model comparison
- Precision, Recall, F1 and ROC-AUC evaluation

---


## 📚 Currently Learning

- Machine Learning
- Deep Learning
- Natural Language Processing
- Transformers
- Large Language Models
- Probability & Statistics
- Data Structures & Algorithms
- SQL

---

## 🤝 Connect With Me

### LinkedIn

[linkedin.com/in/lata-bharati-04575a1a0](https://www.linkedin.com/in/lata-bharati-04575a1a0/)
