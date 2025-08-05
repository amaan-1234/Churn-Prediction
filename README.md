## 📦 Customer Churn Prediction using Machine Learning

This project aims to predict customer churn in a telecommunications company using supervised machine learning techniques. By analyzing customer behavior, service usage, and demographic information, we build a predictive model that identifies customers likely to leave the service.

---

### 📌 Table of Contents

* [📈 Project Overview](#-project-overview)
* [🧠 Machine Learning Approach](#-machine-learning-approach)
* [🗃️ Dataset](#️-dataset)
* [🛠️ Features](#️-features)
* [📊 Exploratory Data Analysis](#-exploratory-data-analysis)
* [⚙️ Model Training & Evaluation](#️-model-training--evaluation)
* [📁 Project Structure](#-project-structure)
* [📌 Requirements](#-requirements)
* [🚀 How to Run](#-how-to-run)
* [📚 Future Improvements](#-future-improvements)
* [📜 License](#-license)

---

### 📈 Project Overview

Customer churn is a critical metric in the telecom industry, as acquiring new customers costs significantly more than retaining existing ones. This project focuses on building a robust classification model that predicts whether a customer will churn based on historical data. The solution is designed to assist businesses in improving customer retention through targeted strategies.

---

### 🧠 Machine Learning Approach

We followed a structured pipeline:

1. Data Cleaning & Preprocessing
2. Exploratory Data Analysis (EDA)
3. Feature Engineering
4. Model Training (Random Forest Classifier)
5. Performance Evaluation
6. Insights and Interpretability

---

### 🗃️ Dataset

* **Source**: [IBM Sample Telco Churn Dataset]
* **Rows**: \~7,043 customer records
* **Features**: 21 attributes including:

  * Customer demographic info
  * Service usage (Internet, Phone, Streaming)
  * Contract details (Monthly, Yearly)
  * Payment methods
  * Charges (Monthly, Total)
  * Target: `Churn` (Yes/No)

---

### 🛠️ Features

| Feature Type     | Examples                        |
| ---------------- | ------------------------------- |
| Demographic      | Gender, SeniorCitizen, Partner  |
| Service-related  | InternetService, StreamingTV    |
| Contract/Account | Contract, PaymentMethod, Tenure |
| Financial        | MonthlyCharges, TotalCharges    |
| Target           | Churn (Yes = left, No = stayed) |

Categorical features were label-encoded or one-hot encoded. Numerical features were standardized for model training.

---

### 📊 Exploratory Data Analysis

EDA included:

* Class distribution of churn vs. retained
* Histograms of Monthly & Total Charges
* Correlation matrix of numeric features
* Churn rates by Contract Type, Internet Service, Tenure

📌 Key Insights:

* Month-to-month contracts had higher churn
* Customers with fiber optic internet churned more
* Shorter tenures correlated with higher churn

---

### Screenshots

<img width="1613" height="1014" alt="image" src="https://github.com/user-attachments/assets/48d8e16a-6529-4f67-9a3b-b5db2044ef2b" />

<img width="1937" height="1292" alt="image" src="https://github.com/user-attachments/assets/5234d1e0-0a6c-4988-a2b5-946bd0f4aea2" />

<img width="2699" height="712" alt="image" src="https://github.com/user-attachments/assets/b7390fde-3c2a-4add-9ba1-9dade863cad2" />

<img width="2142" height="1026" alt="image" src="https://github.com/user-attachments/assets/8f40699b-168f-4c44-a166-65ca1d64575e" />

<img width="2100" height="1267" alt="image" src="https://github.com/user-attachments/assets/15d31772-1f6d-4b03-94a3-6bb8967fce76" />


### ⚙️ Model Training & Evaluation

* **Model Used**: Random Forest Classifier
* **Data Split**: 80% train / 20% test
* **Metrics Evaluated**:

  * Accuracy
  * Precision
  * Recall
  * F1 Score
  * Confusion Matrix
  * ROC-AUC Curve

✅ Achieved approximately:

* **Accuracy**: \~80%
* **F1-score**: Balanced performance on both churn and non-churn classes

---

### 📁 Project Structure


│
├── M_Churn_Prediction.ipynb    # Main notebook
├── README.md                   # Project documentation



---

**Main Libraries**:

* pandas
* numpy
* scikit-learn
* seaborn
* matplotlib

---

### 🙋‍♂️ Author

**Amaan Mohamed**
🔗 [LinkedIn](https://www.linkedin.com/in/amaan-m-5144b6123/) 
Feel free to connect or reach out for collaboration or feedback!

---
