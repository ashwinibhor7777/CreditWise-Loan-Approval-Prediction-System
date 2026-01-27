# CreditWise-Loan-Approval-Prediction-System
Loan approval prediction system using ML with Streamlit deployment and imbalanced data handling.


## 📌 Project Overview

**CreditWise** is a supervised machine learning–based loan approval prediction system designed to help financial institutions make **accurate, fast, and unbiased** loan approval decisions. The system analyzes applicant financial, personal, and credit-related data to predict whether a loan should be **Approved (1)** or **Rejected (0)** before final human verification.

This project simulates a real-world banking use case in India, covering both **urban and rural** loan applicants.

---

## 🏦 Problem Statement

A mid-sized financial company, **SecureTrust Bank**, offers personal and home loans across India. Traditionally, loan officers manually verify applications by reviewing income proofs, employment details, credit history, and other documents.

### 🚨 Challenges with the Manual Process

1. **Time-consuming & inconsistent decisions**
2. **Bias and human error**
3. **Business loss** – eligible customers sometimes get rejected
4. **Financial risk** – high-risk customers sometimes get approved

### 🎯 Objective

To build an **Intelligent Loan Approval System** powered by **Machine Learning** that:

* Automatically analyzes applicant details
* Learns patterns from historical data
* Predicts loan approval decisions accurately
* Reduces bias and processing time

---

## 🤖 Solution Approach

The proposed system uses **Supervised Machine Learning** techniques to classify loan applications as **Approved** or **Rejected** based on historical loan data.

### Key Highlights:

* Binary classification problem
* Target-driven prediction (Loan_Approved)
* Data-driven and unbiased decision-making

---

## 📊 Dataset Description

Each row in the dataset represents a **loan applicant** with multiple attributes describing their personal, financial, and credit information.

### 🗂️ Features Description

| Column Name                | Description                             |
| -------------------------- | --------------------------------------- |
| Applicant_ID               | Unique applicant identifier             |
| Applicant_Income           | Monthly income of applicant             |
| Coapplicant_Income         | Monthly income of co-applicant          |
| Employment_Status          | Salaried / Self-Employed / Business     |
| Age                        | Applicant age                           |
| Marital_Status             | Married / Single                        |
| Dependents                 | Number of dependents                    |
| Credit_Score               | Credit bureau score                     |
| Existing_Loans             | Number of active loans                  |
| DTI_Ratio                  | Debt-to-Income ratio                    |
| Savings                    | Savings balance                         |
| Collateral_Value           | Value of collateral provided            |
| Loan_Amount                | Loan amount requested                   |
| Loan_Term                  | Loan duration (months)                  |
| Loan_Purpose               | Home / Education / Personal / Business  |
| Property_Area              | Urban / Semi-Urban / Rural              |
| Education_Level            | Graduate / Postgraduate / Undergraduate |
| Gender                     | Male / Female                           |
| Employer_Category          | Govt / Private / Self                   |
| **Loan_Approved (Target)** | **1 = Approved, 0 = Rejected**          |

---

## 🧠 Machine Learning Workflow

1. Data Cleaning & Preprocessing
2. Exploratory Data Analysis (EDA)
3. Feature Encoding & Scaling
4. Train-Test Split
5. Model Training (Supervised Learning)
6. Model Evaluation
7. Loan Approval Prediction

---

## 🛠️ Technologies Used

* Python 🐍
* Pandas & NumPy
* Matplotlib & Seaborn (EDA & visualization)
* Scikit-learn (ML models & preprocessing)

---

## 📈 Model Type

* **Supervised Learning**
* **Binary Classification**

### Algorithms Used

* **Logistic Regression** – baseline linear classifier for probability-based loan approval
* **K-Nearest Neighbors (KNN)** – distance-based model to capture similarity between applicants
* **Naive Bayes (NB)** – probabilistic model assuming feature independence

These models were trained and evaluated to compare performance and select the most suitable approach for loan approval prediction.

---

## ✅ Expected Outcomes

* Faster loan approval decisions
* Reduced human bias
* Improved customer satisfaction
* Lower financial risk for banks

---

## 👤 Author

**Ashwini Bhor**
📧 Email: [ashwinibhor2301@gmail.com](mailto:ashwinibhor2301@gmail.com)

---

## 📌 Note

This project is built for **learning, academic, and portfolio purposes** and closely resembles real-world banking ML applications.

⭐ If you find this project helpful, feel free to star the repository!
