# 📊 Customer Churn Prediction using IBM Telco Dataset

## 📌 Project Overview

Customer churn is a critical business challenge for telecom and subscription-based companies, as retaining existing customers is significantly more cost-effective than acquiring new ones.

This project leverages the **IBM Telco Customer Churn Dataset** to analyze customer behavior, identify churn drivers, and build predictive classification models that help businesses proactively reduce customer attrition.

The workflow includes **data preprocessing, exploratory data analysis (EDA), feature engineering, machine learning model development, and performance evaluation using key metrics**.

---

## 🎯 Key Objectives

✔ Analyze customer churn behavior and identify risk patterns
✔ Perform Exploratory Data Analysis (EDA) to uncover insights
✔ Clean and preprocess raw customer data
✔ Encode categorical variables for machine learning models
✔ Train multiple classification models for churn prediction
✔ Compare models using evaluation metrics
✔ Provide business recommendations for retention strategies

---

## 📊 Dataset Information

* **Dataset:** IBM Telco Customer Churn Dataset
* **Total Records:** 7,043 customers
* **Features:** 21 variables
* **Target Variable:** `Churn (Yes / No)`

### Key Variables Included:

* Customer Demographics
* Tenure
* Contract Type
* Monthly Charges
* Total Charges
* Internet Service
* Payment Method
* Online Security
* Tech Support
* Streaming Services

---

## 🔍 Exploratory Data Analysis (EDA)

The project includes detailed visual analysis of customer churn trends:

### 📈 Visualizations Performed

✔ Churn Distribution Analysis
✔ Contract Type vs Churn
✔ Monthly Charges vs Churn
✔ Tenure vs Churn
✔ Senior Citizen vs Churn
✔ Correlation Heatmap
✔ Service-wise churn comparison

---

## 🤖 Machine Learning Models Implemented

The following classification models were trained and evaluated:

* Logistic Regression
* Decision Tree Classifier
* Random Forest Classifier
* K-Nearest Neighbors (KNN)

---

## 📉 Model Performance Comparison

| Model               | Accuracy |
| ------------------- | -------- |
| Logistic Regression | ~79%     |
| Random Forest       | ~78–80%  |
| KNN                 | ~75–77%  |
| Decision Tree       | ~72–74%  |

---

## 📌 Detailed Metrics (Logistic Regression)

* **Accuracy:** ~79%
* **ROC AUC Score:** 0.70
* **Precision (Churn = Yes):** 0.62
* **Recall (Churn = Yes):** 0.52
* **F1 Score:** ~0.56

### Evaluation Techniques Used:

✔ Accuracy Score
✔ Precision Score
✔ Recall Score
✔ F1 Score
✔ ROC Curve
✔ Confusion Matrix
✔ Classification Report

---

## 💡 Key Business Insights

🔹 Customers with **month-to-month contracts** are more likely to churn.
🔹 Customers paying **higher monthly charges** show increased churn probability.
🔹 Long-tenure customers are more loyal.
🔹 Customers using support/security services churn less frequently.
🔹 Early churn prediction enables targeted retention campaigns.

---

## 🚀 Business Recommendations

✔ Offer discounts for month-to-month customers
✔ Promote annual and long-term plans
✔ Improve customer support quality
✔ Identify high-risk churn customers using ML model
✔ Launch personalized retention offers

---

## 🛠️ Tech Stack

* **Programming Language:** Python
* **Libraries:** Pandas, NumPy
* **Visualization:** Matplotlib, Seaborn
* **Machine Learning:** Scikit-learn
* **Environment:** Jupyter Notebook

---

## 📁 Deliverables

✔ Cleaned Dataset
✔ Jupyter Notebook
✔ Visualizations
✔ Trained Models
✔ Performance Comparison
✔ Business Insights Report

---

## 👨‍💻 Author

**Milan Kumar Suthar**
M.Sc. Statistics & Computing, BHU
Aspiring Data Analyst | Machine Learning Enthusiast

---

## ⭐ If you found this project useful, feel free to star the repository.
