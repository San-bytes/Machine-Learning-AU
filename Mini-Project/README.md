# Customer Churn Prediction

## 📌 Project Overview
This project aims to predict customer churn using machine learning techniques. 
Customer churn refers to customers leaving a service, and predicting it helps businesses take preventive actions.

---

## 🎯 Objective
To build a machine learning model that can predict whether a customer will churn based on various features such as tenure, charges, and services used.

---

## 📂 Dataset
- Dataset used: Telco Customer Churn Dataset  
- Contains customer details like demographics, services, and billing information  

---

## ⚙️ Steps Performed

### 1. Data Loading
- Loaded dataset using pandas  

### 2. Data Cleaning
- Converted `TotalCharges` to numeric  
- Handled missing values  
- Removed unnecessary columns like `customerID`  

### 3. Exploratory Data Analysis (EDA)
- Visualized churn distribution  
- Analyzed relationship between tenure, charges, and churn  

### 4. Data Encoding
- Converted categorical variables using one-hot encoding  

### 5. Handling Class Imbalance
- Applied SMOTE to balance the dataset  

### 6. Model Building
- Decision Tree Classifier  
- Random Forest Classifier  

### 7. Model Evaluation
- Accuracy score  
- Confusion matrix  
- Classification report  

---

## 🤖 Models Used
- Decision Tree  
- Random Forest  

---

## 📊 Results

- Initial model had higher accuracy but poor recall for churn class  
- After applying SMOTE:
  - Recall for churn improved significantly  
  - Model became better at identifying churn customers  

---

## 📈 Key Insight
Identifying churn customers is more important than overall accuracy, as it helps businesses retain customers.

---

## ✅ Conclusion
Random Forest with SMOTE performed better in detecting churn customers.  
This model can help businesses take proactive steps to reduce customer loss.

---

## 🔗 Repository Structure
- `Custo-Churn-Prediction.ipynb` → Main notebook  
- `Telco-Customer-Churn.csv` → Dataset  
- `README.md` → Project documentation  

---

## 👨‍💻 Author
- Prasannashree B
