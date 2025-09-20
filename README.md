<p align="center">
  <img src="LoanApproval.jpg" alt="Loan Approval Prediction" width="600"/>
</p>

# 🏦 **LOAN APPROVAL PREDICTION**

## 🧾 **PROJECT DESCRIPTION**
*Predict whether a loan application will be approved or not based on applicant details using Machine Learning.*

This project applies **data preprocessing, SMOTE balancing, and classification models** such as **Logistic Regression** and **Decision Tree Classifier** to determine loan approval outcomes.

---

## 📚 **TABLE OF CONTENTS**
- 📌 Project Title  
- 🧾 Project Description  
- 📊 Dataset Information  
- 🛠️ Tech Stack Used  
- 🧠 Workflow & Methodology  
- 📈 Model Performance  
- 🧪 How to Use  
- 🏁 Results  
- 👥 Author  

---

## 📊 **DATASET INFORMATION**
- **File Name**: `loan_approval_dataset.csv`  
- **Format**: CSV  
- **Key Columns**:
  - `loan_id` (removed during preprocessing)  
  - `gender`  
  - `married`  
  - `dependents`  
  - `education`  
  - `self_employed`  
  - `applicant_income`  
  - `coapplicant_income`  
  - `loan_amount`  
  - `loan_amount_term`  
  - `credit_history`  
  - `property_area`  
  - `loan_status` (target variable ✅)  

---

## 🛠️ **TECH STACK USED**
- **Programming Language**: 🐍 Python 3  
- **Libraries & Tools**:
  - `pandas`, `numpy`  
  - `scikit-learn`  
  - `matplotlib`, `seaborn`  
  - `imblearn` (for SMOTE)  

---

## 🧠 **WORKFLOW & METHODOLOGY**
1. **Load and Explore Data**  
   - Handle missing values  
   - Drop unnecessary column: `loan_id`  

2. **Data Preprocessing**  
   - Encode categorical variables  
   - Scale numeric variables  
   - Balance dataset using **SMOTE**  

3. **Model Training**  
   - Logistic Regression  
   - Decision Tree Classifier  

4. **Model Evaluation**  
   - Accuracy Score  
   - Confusion Matrix  
   - Precision, Recall, F1 Score  
   - Classification Report  

---

## 📈 **MODEL PERFORMANCE**
| Model                   | Accuracy |
|--------------------------|----------|
| Logistic Regression      | ~0.93    |
| Decision Tree Classifier | ~0.97    |

*(Values may vary depending on train/test split)*

---

## 🧪 **HOW TO USE**
- Open the notebook: `Loan_Approval_Prediction.ipynb`  
- Run all cells in order  
- Observe preprocessing, model training, and evaluation steps  
- Test predictions by passing custom applicant data  

---

## 🏁 **RESULTS**
- ✔️ Built a machine learning model for loan approval prediction  
- ✔️ Compared **Logistic Regression** and **Decision Tree** models  
- ✔️ Applied **SMOTE** to handle class imbalance  
- ✔️ Achieved ~97% accuracy with Decision Tree Classifier  

---

## 👥 **AUTHOR**
- **Arghya Chakraborty**  

---
