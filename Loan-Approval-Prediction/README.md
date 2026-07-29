# 🏦 Loan Approval Prediction

A Machine Learning project that predicts whether a loan application will be **Approved** or **Rejected** based on applicant details using different classification algorithms.

---

## 📌 Project Overview

Banks receive thousands of loan applications every day. This project helps automate the loan approval process by predicting loan status using machine learning.

---

## 📂 Dataset

**Dataset:** Loan Approval Prediction Dataset

**Target Column:** `Loan_Status`

**Features:**
- Gender
- Married
- Dependents
- Education
- Self_Employed
- ApplicantIncome
- CoapplicantIncome
- LoanAmount
- Loan_Amount_Term
- Credit_History
- Property_Area

---

## 🛠 Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib

---

## 📊 Data Preprocessing

- Loaded dataset
- Checked dataset information
- Checked missing values
- Filled missing values
- Encoded categorical columns using LabelEncoder
- Created data visualizations
- Generated Correlation Heatmap
- Split dataset into training and testing sets

---

## 🤖 Machine Learning Models

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- K-Nearest Neighbors (KNN)

---

## 📈 Model Evaluation

Models were evaluated using:

- Accuracy Score
- Confusion Matrix
- Classification Report
  - Precision
  - Recall
  - F1-Score

---

## 🏆 Model Comparison

| Algorithm | Accuracy |
|-----------|----------|
| Logistic Regression | **78.86% ⭐** |
| Random Forest | 78.05% |
| Decision Tree | 69.11% |
| KNN | 61.79% |

**Best Model:** Logistic Regression

---

## 📊 Visualizations

- Bar Plot
- Correlation Heatmap

---

## 📁 Project Structure

```
Loan-Approval-Prediction/
│
├── loan_approval.csv
├── Loan_Approval_Prediction.ipynb
├── loan_model.pkl
├── README.md
├── requirements.txt
└── LICENSE (Optional)
```

---

## 🚀 How to Run

1. Clone the repository

```bash
git clone https://github.com/csarman-ds/Loan-Approval-Prediction.git
```

2. Install dependencies

```bash
pip install -r requirements.txt
```

3. Open Jupyter Notebook

```bash
jupyter notebook
```

4. Run all cells.

---

## 📌 Future Improvements

- Hyperparameter Tuning
- Cross Validation
- Feature Engineering
- Streamlit Web App
- Flask Deployment

---

## 👨‍💻 Author

**Arman**

B.Sc. Data Science Student

GitHub: https://github.com/csarman-ds

---

# ⭐ If you found this project useful, please Star this Repository!