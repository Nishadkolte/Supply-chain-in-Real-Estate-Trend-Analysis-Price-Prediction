# Supply-chain-in-Real-Estate-Trend-Analysis-Price-Prediction
👨‍💻 By: Nishad Ravindra Kolte 📅 EPBA 02 | 2023–24 🎓 Adani Institute of Digital Technology Management &amp; Carleton University
---

## 📌 Project Overview

This project analyzes and predicts real estate pricing and registration trends using actual data from expos held in Gujarat and Madhya Pradesh. With a combination of data cleaning, Power BI visualization, time series forecasting, and machine learning concepts, it helps uncover actionable insights for developers, investors, and marketers.

---

## 🚀 Objectives

- Analyze buyer preferences based on property type, location, and budget
- Forecast future demand using time series modeling
- Build interactive dashboards for real-time insights
- Explore machine learning concepts for property valuation and segmentation
- Ensure data privacy and security throughout the project lifecycle

---

## 🧠 Problem Statement

The real estate sector faces challenges such as:
- Inaccurate property valuation
- Poor prediction of market trends
- Inability to extract insights from large, unstructured datasets

This project aims to address these gaps with robust data analytics and visualization tools.

---

## 🔧 Project Workflow

### 1️⃣ Data Cleaning & Preparation
- Removed missing values, outliers, and duplicates
- Categorized property types and budget ranges
- Enriched dataset with new calculated columns

### 2️⃣ Visualization using Power BI
- Built an interactive dashboard with:
  - 📍 Location-based demand heatmaps
  - 💰 Budget distribution pie charts
  - 🧾 Registration type tables
  - 🕹️ Filterable user interactions

### 3️⃣ Time Series Forecasting
- Used Least Squares Regression for monthly registration trend prediction
- Found a 44% R² indicating moderate predictive accuracy
- Incorporated autocorrelation checks (Durbin-Watson = 1.50)

### 4️⃣ Machine Learning Concepts *(Theoretical Scope)*
- **Supervised Learning**: Linear Regression, Decision Trees
- **Unsupervised Learning**: K-Means Clustering for segmentation
- **Deep Learning**: Neural networks for image & pattern recognition
- **Computer Vision**: Discussed relevance in real estate applications

### 5️⃣ Data Security Best Practices
- Excel-based encryption & access control
- Data validation, audit trails, and recovery strategies implemented

---

## 📈 Key Findings

| Property Type       | Locations                             | Budget Range   | Top Registrations |
|---------------------|----------------------------------------|----------------|-------------------|
| 1 RK / Studio       | Naroda, Narol                          | < ₹30 Lacs     | 211               |
| 1 BHK               | Lambha, Naroda                         | < ₹30 Lacs     | 268               |
| 2 BHK               | Gift City, Kudasan                     | ₹30–50 Lacs    | 1333              |
| 3 BHK               | Gift City, Chandkheda                  | ₹50–85 Lacs    | 1730              |
| 4+ BHK / Villas     | Shilaj, Vastrapur                      | ₹2.25 Cr+      | 713+              |
| Office Spaces       | Gift City, Kudasan                     | ₹50–75 Lacs    | 128               |

---

## 🖥️ Dashboard Preview

You can explore the Power BI dashboard (file: `dashboard.pbix`) for:
- 🧠 Data storytelling
- 📍 Location-wise insights
- 📊 Budget category performance
- 📈 Forecast trends over time


---

## 📂 Project Structure

```bash
real-estate-trend-analysis/
├── data/
│   └── raw_data.csv
├── notebooks/
│   ├── data_cleaning.ipynb
│   └── time_series_model.ipynb
├── powerbi/
│   └── dashboard.pbix
├── reports/
│   └── EPBA_Capstone_Report_NishadKolte.pdf
└── README.md
