PhonePe-Data-Analysis-PowerBI/
│
├── 📊 Dashboard_Screenshots/
│   ├── Homepage_Overview.png            
│   ├── Insurance_Analysis.png           
│   └── Failed_Payments_DeepDive.png     
│
├── 🛠️ Dataset/
│   └── PhonePe_Final_Dataset.xlsx       
│
├── 📐 PowerBI_File/
│   └── PhonePe_Analysis_Dashboard.pbix  
└── 📄 README.md

# 📱 PhonePe End-to-End Data Analysis & BI Project (Power BI)

![Project Status](https://shields.io)
![Tech](https://shields.io)

## 📌 Project Overview
This repository contains an End-to-End Business Intelligence Project focused on analyzing transaction data from PhonePe, India's leading fintech and UPI application. Utilizing a comprehensive fintech database, this project tracks overall financial volume, identifies transaction friction points, and evaluates service breakdowns across Insurance, Loans, Money Transfers, and Recharge & Bills.

The final deliverable is an interactive 5-page enterprise dashboard built with a customized fintech-driven UX (Purple Theme) to assist product managers in monitoring payment health and minimizing user retention issues.

---

## 📊 Interactive Dashboard Walkthrough
*Below are the previews of the production-ready Power BI dashboard tabs:*

### 1. Unified Homepage & Executive Summary
![Homepage Summary](Dashboard_Screenshots/Homepage_Overview.png)

### 2. Insurance & Services Deep-Dive
![Insurance Breakdown](Dashboard_Screenshots/Insurance_Analysis.png)

---

## 🛠️ Tech Stack & Methods Demonstrated
- Data Loading & ETL: Imported raw multi-tab databases into Power BI Desktop, verifying table structures, tracking data types, and ensuring text alignment through Power Query.
- Fintech UI/UX Design: Implemented a transparent overlay system with customized purple hex-codes matching PhonePe's official brand identity.
- Dynamic Filtering: Consolidated multi-page filtering by attaching a centralized date-range slicer connected across all semantic models.
- Interactive Navigation: Implemented dynamic Page Navigation actions mapped to shape clusters for a seamless application feel.

---

## 📈 Key Technical Metrics & Project KPIs
The data infrastructure processes and visualizes the following critical operational counters:
- Total Financial Volume: Summation of all successfully processed transaction amounts across the entire ecosystem.
- Core Volume Split: Tracking total system transactions versus specific failed transaction instances.
- Transaction Health Ratios: Measuring absolute success metrics against involuntary transaction drop-offs.
- Service Categories Tracked: Insurance (Term, Car, Bike, Health), Loans, Transfers, and Bill Recharges.

---

## 💡 Core Business Problems Addressed & Solutions

### 1. Mitigation of Transaction Friction (Failed Payment Analysis)
- Business Problem: Payment failures degrade user trust, driving customers toward alternative platforms. Monitoring failure root-causes is critical to reducing churn.
- Data Solution: Isolated failed payments to track categorical issues such as Server Errors, Wrong PINs, Insufficient Balance, and Bank Server Disconnects.
- Actionable Insight: The dashboard establishes an alert system for payment failures; product teams can easily cross-examine specific error spikes to locate bad partner bank servers and deploy fixes promptly.

### 2. Service Performance Tracking (Volume vs. Transaction Count)
- Business Problem: Assessing how individual fintech streams contribute to overall transaction volumes versus absolute financial values.
- Data Solution: Structured dedicated sub-charts comparing total billing across verticals. For instance, mapping transaction splits in the Insurance sector exposed the distribution among Car, Bike, Health, and Term Life categories.
- Actionable Insight: Identified that while certain verticals show low absolute transaction counts, they hold significant weight in volume value (e.g., Loan payments vs. small-ticket Mobile Recharges), helping executive management allocate product maintenance budgets efficiently.

---

## 📂 Repository Contents
- /PowerBI_File: Contains the production file (.pbix) with integrated data models and layout configurations.
