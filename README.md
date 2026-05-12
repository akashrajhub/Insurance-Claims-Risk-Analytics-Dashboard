# Insurance Claims & Risk Analytics Dashboard

An end-to-end Power BI analytics solution designed to monitor insurance claim performance, detect operational leakage, analyze overpayments, and identify high-risk claim behavior across patient and hospital networks.

---

# 📌 Project Overview

Insurance companies process millions of claims every year, making it difficult to detect operational inefficiencies, overpayments, and claim leakage.

This project was developed to:
- Monitor insurance claim operations
- Identify financial leakage and overpayments
- Analyze patient & hospital-level claim behavior
- Detect utilization risk patterns
- Simulate leakage reduction scenarios
- Improve claim governance and profitability

The dashboard analyzes approximately **1.25M insurance claim records** and provides interactive drill-through analysis, scenario simulation, and operational insights.

---

# 🎯 Business Objectives

- Track claims, approvals, payouts, and profitability
- Identify overpayment leakage drivers
- Detect high-frequency claim patterns
- Analyze diagnosis-level financial impact
- Investigate patient & hospital-level utilization
- Simulate leakage reduction scenarios
- Support risk-based claim governance

---

# 🛠️ Tools & Technologies

- MySQL
- Power BI
- Power Query
- DAX
- Star Schema Data Modeling
- What-If Parameters
- Bookmarks & Drill-through
- Decomposition Tree
- KPI Cards & Advanced Visuals

---

# 📂 Dataset Information

The dataset includes:
- Claim Amount
- Approved Amount
- Overpayment
- Patient Information
- Hospital Information
- Policy Type
- Diagnosis
- Claim Status
- Premium Paid
- Claim Date
- Risk Indicators

### Dataset Size
- ~1.25 Million Records

---

# 📊 Dashboard Pages

## 1️⃣ Overview Analysis

Provides a high-level summary of:
- Claims Volume
- Approved Payout
- Profitability
- Claim Trends
- Diagnosis-Level Profit Analysis
- Claim Status Distribution

### Key Insights
- Claim approvals increased consistently over time.
- Overpayments significantly impacted profitability.
- Basic & Standard policies contributed most to leakage.
- Heart Disease & Cancer generated major financial losses.

---

## 2️⃣ Financial Analysis

Focused on financial leakage and profit optimization.

### Includes
- Overpayment Distribution
- Profit vs Potential Profit
- Diagnosis-Level Profit Opportunity
- Overpayment Severity Analysis

### Key Insights
- Smaller claims contributed disproportionately to leakage.
- Significant unrealized profit opportunity exists.
- Overpayments were concentrated within specific diagnoses.

---

## 3️⃣ Risk Analysis

Risk-focused operational monitoring and leakage analysis.

### Includes
- Leakage Growth Trends
- Policy-Level Overpayment Analysis
- Leakage Contribution by Diagnosis
- Scenario Simulation

### What-If Scenario Analysis
Implemented dynamic leakage reduction simulation using What-If Parameters.

### Scenario Metrics
- Adjusted Profit
- Leakage Saved
- Efficiency Gain
- Profit Growth

### Key Insights
- Leakage increased year-over-year.
- Heart Disease and Accident diagnoses showed highest leakage exposure.
- Operational controls could significantly improve profitability.

---

## 4️⃣ Deep Dive Analysis

Advanced investigation page for patient and hospital-level analysis.

### Features
- Bookmark-Based Navigation
- Patient vs Hospital Analysis
- Decomposition Tree
- Drill-through Pages
- Risk Segmentation

### Key Insights
- Smoker and overweight patient groups showed higher overpayment exposure.
- Private hospitals contributed more operational leakage.
- High-frequency claims revealed utilization risk patterns.
- Certain cities and hospitals showed concentrated claim costs.

---

# 📈 Key KPIs

| KPI | Value |
|---|---|
| Claims Volume | 1.25M |
| Approved Payout | 83.71bn |
| Net Profit | 25.88bn |
| Profit Opportunity | 54.68bn |
| Total Overpayment | 28.81bn |
| Approval Efficiency | 77.02% |
| Leakage Index | 34.41% |

---

# 🚨 Business Recommendations

- Double-check all claims before approval to reduce unnecessary overpayments and leakage.
- Monitor high-frequency claims and flag unusual claim activity early.
- Introduce stricter review processes for high-value and repeated claims.
- Conduct regular audits and risk-based reviews to strengthen claim quality control.
- Flag patients or hospitals with frequent claim activity for additional verification.
- Implement automated claim limit controls to prevent payouts beyond policy coverage and approve only eligible amounts when limits are exceeded.

---

# ⚡ Performance Optimization

To improve dashboard performance and scalability:
- Implemented Star Schema modeling
- Used bookmark-based navigation
- Reduced visual load using dynamic views
- Optimized DAX measures
- Used drill-through pages for detailed analysis

---

# 📌 Project Highlights

✅ 1.25M+ Claim Records Analyzed  
✅ Leakage & Overpayment Monitoring  
✅ What-If Scenario Simulation  
✅ Patient & Hospital Drill-through Analysis  
✅ Operational Risk Segmentation  
✅ Advanced DAX Measures  
✅ Bookmark-Based Interactive Navigation  
✅ Executive-Level Dashboard Design

---

# 📷 Dashboard Preview

## Overview Dashboard
<img width="1438" height="811" alt="Overview" src="https://github.com/user-attachments/assets/e86b9751-62fe-45f2-a6ff-e72bdf5548a5" />



## Financial Analysis
<img width="1440" height="811" alt="Financial" src="https://github.com/user-attachments/assets/73ebee3c-b211-4761-bd55-bb7ffc8da9be" />


## Risk Analysis
<img width="1446" height="811" alt="Risk" src="https://github.com/user-attachments/assets/46742c0c-c352-4567-a992-de33069d0652" />


## Deep Dive Analysis
<img width="1446" height="813" alt="Deep" src="https://github.com/user-attachments/assets/419e0949-409e-487d-93ee-a2dc1b5b5228" />


---

# 📁 Repository Structure

```bash
Insurance-Claims-Risk-Analytics/
│
├── Dashboard/
│   └── Insurance Claims & Risk Analytics Dashboard.pbix
│
├── Dataset/
│   └── insurance_claims_dataset.csv
│
├── Screenshots/
│   ├── overview.png
│   ├── financial_analysis.png
│   ├── risk_analysis.png
│   └── deep_dive.png
│
├── README.md
└── LICENSE
```

👨‍💻 Author
AKASH RAJ

🌐 Portfolio: https://akashrajhub.github.io/

📄 Resume: https://akashrajhub.github.io/Akash-Raj-BI-Analyst-Resume.pdf

💻 GitHub: https://github.com/akashrajhub
