# 🏥 Healthcare Provider Fraud Detection Analysis

## 📌 Project Overview
This project focuses on analyzing healthcare claims data to identify patterns that support **fraud detection in healthcare providers**. The analysis emphasizes distinguishing **legitimate high-cost care** from potentially fraudulent behavior.

Dataset Source: Kaggle – Healthcare Provider Fraud Detection Analysis

---

## 📊 Dataset Description
The dataset includes:
- **Beneficiary Data:** Demographics, chronic conditions, date of birth, date of death
- **Inpatient Claims:** Hospital admissions, procedures, reimbursements
- **Outpatient Claims:** Clinic visits, procedures, reimbursement amounts

Total Records: **138,556 beneficiaries**

---

## 🛠️ Tools & Technologies
- Python
- Pandas & NumPy
- Matplotlib & Seaborn
- Jupyter Notebook

---

## 🔍 Key Analysis Steps

### 1️⃣ Data Cleaning & Feature Engineering
- Converted DOB and DOD into datetime format
- Created:
  - **Status** column (Alive / Dead)
  - **Age** column
- Handled missing and categorical values

### 2️⃣ Exploratory Data Analysis (EDA)
- Alive vs Deceased beneficiary distribution
- Chronic disease prevalence analysis
- Gender and race-based demographic analysis
- Age distribution and outlier detection

### 3️⃣ Chronic Disease Analysis
- Identified most prevalent chronic conditions
- Compared disease distribution between alive and deceased patients
- Analyzed multimorbidity and disease correlations

### 4️⃣ Visualizations
- Count plots for demographics
- Bar charts for disease prevalence
- Box plots for age distribution
- Heatmaps for chronic disease correlations

---

## 📈 Key Insights
- Majority of beneficiaries are alive, with fewer recorded deaths
- Chronic diseases significantly increase healthcare utilization
- Older age groups naturally incur higher medical costs
- **High claim amounts alone should not be treated as fraud indicators**
- Multimorbidity is a major driver of healthcare expenses

---

## 🎯 Conclusion
This project highlights the importance of **context-aware fraud detection**, ensuring providers treating complex patients are not unfairly flagged while improving fraud monitoring accuracy.

---

## 📂 Repository Structure
- `notebooks/` – Jupyter notebooks for analysis
- `data/` – Dataset (not included due to size)
- `visualizations/` – Generated plots and charts

Hira Imran Aspiring Data Analyst | Power BI Developer 📍 Pakistan

📫 Contact: (imranhira26@gmail.com) 🔗 LinkedIn: (www.LinkedIn.com/in/ms-hira-imran)

⭐ Support

If you like this project, consider giving it a ⭐ on GitHub!
## 🤝 Connect
If you found this project useful or have feedback, feel free to connect with me on LinkedIn!
