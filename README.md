# 💳 CreditWise Loan Approval System

## 📌 Project Overview
The CreditWise Loan Approval System is a Machine Learning project designed to automate the loan approval process. Traditional manual verification is time-consuming and often inconsistent. This system predicts whether a loan application should be **Approved (1)** or **Rejected (0)** based on applicant data.

---

## 🎯 Problem Statement
Financial institutions face challenges such as:
- Rejecting eligible customers
- Approving high-risk applicants

This project uses historical data to build a predictive model that ensures:
- Faster decision-making
- Reduced bias
- Improved accuracy

---

## 📊 Dataset Description
Each row represents a loan applicant with features like:
- Applicant Income
- Employment Status
- Credit Score
- Loan Amount
- Property Area
- Loan Purpose
- Gender
- Employer Category  
and more...

Target Variable:
- **Loan_Approved (1 = Approved, 0 = Rejected)**

---

## ⚙️ Technologies Used
- Python 🐍
- NumPy
- Pandas
- Scikit-learn
- Matplotlib / Seaborn (for visualization)

---

## 🔄 Workflow
1. Data Cleaning & Preprocessing
2. Handling Missing Values
3. Encoding Categorical Features (OneHotEncoder)
4. Feature Scaling (if applied)
5. Model Training
6. Model Evaluation & Comparison

---

## 🤖 Models Used
The following machine learning algorithms were implemented and compared:

- Logistic Regression ✅ (Best Performance)
- K-Nearest Neighbors (KNN)
- Gaussian Naive Bayes

---

## 📈 Results
- Logistic Regression gave the highest accuracy among all models.
- KNN performed moderately well.
- GaussianNB was fast but less accurate.

---

## 📊 Evaluation Metrics
- Accuracy
- Confusion Matrix
- Precision & Recall (if used)

---

## 🚀 How to Run
```bash
# Clone the repository
git clone https://github.com/your-username/your-repo-name.git

# Navigate to folder
cd your-repo-name

# Install dependencies
pip install -r requirements.txt

# Run the notebook / script

├── data/
├── notebooks/
├── model/
├── README.md
└── requirements.txt

