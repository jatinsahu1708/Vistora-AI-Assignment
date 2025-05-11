# Vistora-AI-Assignment
# 🧠 Telco Customer Churn – Feature Engineering with Snowflake & Feature Store

## 📌 Project Overview
This project demonstrates an end-to-end feature engineering pipeline using **Snowflake SQL** and a **Feature Store** for machine learning.  
We work with the **Telco Customer Churn dataset** to:
- Clean and transform raw customer data
- Encode and normalize features
- Construct meaningful derived variables
- Store final features in a Feature Store (Snowflake DB)
- Train a churn prediction model using Python

## 🧪 Tools & Technologies

| Tool       | Purpose                           |
|------------|-----------------------------------|
| **Snowflake** | SQL-based data cleaning and transformation |
| **Python (pandas, sklearn)** | ML model training |
| **Snowflake Connector** | Connect Python with Snowflake |
| **Jupyter Notebook** | ML development environment |
| **GitHub** | Code repository |
| **Google Drive** | Video hosting |

---

## 📊 Dataset

- **Source:** [Kaggle - Telco Customer Churn](https://www.kaggle.com/blastchar/telco-customer-churn)
- **Target:** `Churn` column (Yes/No)
- **Records:** 7,043
- **Features:** 20 input columns (services, contract, payments, demographics)

---

## 🧠 Feature Engineering Steps

1. **Raw data upload** and `TotalCharges` conversion
2. **Missing value handling** via row filtering
3. **Binary and one-hot encoding**
4. **Z-score normalization** on numeric features
5. **Constructed features** like:
   - Average Monthly Charge
   - Estimated Customer Lifetime Value (CLV)
   - Tenure Buckets
6. **Stored final features** in `feature_store.telco_customer_churn_features`

---

## 🤖 Model Training

- Used **Random Forest Classifier**
- Trained using Python and Snowflake connector
- Evaluated with `classification_report`

---

## 🎥 Video Walkthrough

📎 Link: _See `[video/video_link.txt](https://drive.google.com/drive/folders/1XaKdgfaKjWYUcgW4iNBGnPsW2rcNvyJ-)`_

---

## 📬 Contact

If you have questions or feedback, feel free to reach out.

---

> _Created by **Jatin** | May 2025_

