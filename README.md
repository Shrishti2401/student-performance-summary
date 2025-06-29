# 🎓 Student Performance Intelligence Dashboard – EdTech Analytics
> ⚠️ **Note:** This project uses anonymized and simulated data for demonstration purposes only. No real student or institutional data has been shared to maintain confidentiality.

### [Click Here For Detailed View](Student_Performance_Analytics_Notebook.ipynb)




This project simulates a real-time analytics solution for an EdTech coaching institute, focused on JEE, BITSAT, Advance, and EAMCET exam performance. The objective was to identify student performance patterns, spot academic risks, and deliver predictive insights to guide intervention and strategy.



## 📌 Project Summary

Led end-to-end analysis of a real EdTech coaching dataset covering 53 exams and 300+ students, using Python for data cleaning and consolidation, and SQL to engineer band logic, thresholds, and performance flags. Developed 4 interactive Tableau dashboards to track academic trends, subject-level strengths, and student participation. Integrated a Python-based regression model to predict JEE scores and identify hidden performance shifts. Delivered insights that flagged 43 at-risk students for academic intervention and surfaced 4 high-potential students for accelerated support — empowering data-driven decisions for coaching leadership.
---

## 🛠 Tools Used

- SQL Server – data cleaning, banding logic, and aggregation

- Python (XGBoost) – data cleaning, prediction of JEE scores using subject-wise and batch-level features

- Tableau Public – visualization of trends, segmentation, and predictions

- Excel – initial dataset standardization and import management




## 📊 Key Metrics Tracked

- Avg Total Marks per student and test

- Participation Rate per exam

- Subject Score Bands per exam type

- Top/Bottom N performers (based on band appearance frequency)

- Predicted Score vs Historical Avg (score gap)

- Risk Flag and Prediction Band indicators

## 📐 Banding & Threshold Logic

#### ✨ Total Marks Band (by Exam Type) (Dynamic Threshold):

- JEE Mains: Low < 80, Medium = 80–160, High > 160

- Advance: Low < 50, Medium = 50–100, High > 100

- BITSAT: Low < 130, Medium = 130–200, High > 200

- EAMCET: Low ≤ 40, Medium = 41–89, High ≥ 90

#### ✍️ Risk Flag Logic:

- ❌ At Risk: Avg Total - Predicted Score >30

- 🟢 High Potential: Avg Total - Predicted Score <-30

- ⚠️ Moderate: prediction aligns with past performance

#### 🎯 Prediction Band:

- 🟢 High ≥ 180

- 🟡 Medium = 120–179

- 🔴 Low < 120





## 📊 Dashboards Overview

### 1. Overall Performance & Trends

- Avg marks over time, participation, performance bands, exam frequency

### 2. Exam Type Summary

- Subject-wise averages and band comparison by exam type

- KPI cards with Min/Max/Avg marks + participation rate

### 3. Top/Bottom N Performance Analysis

- Dynamic thresholds to flag consistently high or low performers

- 100% stacked band breakdown and band frequency

### 4. Score Prediction Dashboard

- Predicted vs Avg marks, Score Gap

- Risk Flags, Prediction Bands, Insight Summary per student
---

## 📌 Disclaimer

This project is built using **anonymized** and **simulated data** to demonstrate data analysis, visualization, and predictive modeling skills. All identifiers (such as student names, IDs, and exact scores) have been removed or replaced. 

This repository does **not contain any confidential or proprietary information** from any institution or organization.







