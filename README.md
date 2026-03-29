# 📊 PhonePe Transaction Insights & Data Visualization

## 🚀 Project Overview
This project is an **end-to-end data analytics solution** built to analyze digital payment data from PhonePe. It extracts raw JSON data, transforms it into structured format, stores it in SQL, and presents insights through an interactive Streamlit dashboard.

---

## 🧾 Project Details

- **Project Type:** Data Analytics (ETL + Dashboard)
- **Contribution:** Individual
- **Author:** Dharminder Singh Virk
- **Domain:** FinTech / Digital Payments / Data Analytics

---

## 📌 Problem Statement
With the rapid growth of digital payment platforms like PhonePe, it is crucial to analyze transaction data to:

- Understand user behavior  
- Identify transaction trends  
- Detect fraud patterns  
- Discover high-performing regions  

---

## 🎯 Objectives

- Extract data from GitHub (PhonePe Pulse)  
- Transform JSON data into structured format  
- Store data in SQLite database  
- Perform SQL-based analysis  
- Create insightful visualizations  
- Build an interactive Streamlit dashboard  
- Identify top-performing states, districts, and pincodes  

---

## 📂 Dataset Description

The dataset is sourced from the **PhonePe Pulse GitHub repository** and includes:

### 🔹 Aggregated Data
- Transaction Type  
- Transaction Count  
- Transaction Amount  

### 🔹 Map Data
- State-level data  
- District-level data  

### 🔹 Top Data
- Top States  
- Top Districts  
- Top Pincodes  

📁 **Data Structure:**
State → Year → Quarter → JSON Files  

---

## 🛠️ Tech Stack

### 💻 Languages & Tools
- Python  
- SQL (SQLite)  
- Streamlit  

### 📚 Libraries
- Pandas  
- Matplotlib  
- Seaborn  
- Plotly  
- PyDeck  

### ⚙️ Platform
- Google Colab  
- GitHub  

---

## 🔄 Project Workflow (ETL Pipeline)

### 1️⃣ Data Extraction
- Cloned dataset from GitHub  
- Loaded JSON files using Python  

### 2️⃣ Data Transformation
- Extracted required fields  
- Converted into Pandas DataFrames  
- Cleaned and formatted data  

### 3️⃣ Data Loading
- Created SQLite database  
- Stored data in tables:
  - aggregated_transaction  
  - map_transaction  
  - top_transaction  
  - top_pincode  

---

## 📊 Data Analysis

Performed SQL queries to generate insights:

- Top Performing States  
- Top Districts  
- Top Pincodes  
- Year-wise Growth  
- Quarterly Trends  
- Transaction Type Analysis  
- User Engagement  
- Insurance Insights  

---

## 📈 Visualizations

- 📊 Bar Charts  
- 📉 Line Charts  
- 🥧 Pie Charts  
- 🔥 Heatmaps  
- 📍 District Analysis  
- 🗺️ Choropleth Maps  
- 📊 Histogram  

---

## 📊 Key Features

- KPI Metrics Dashboard  
- Interactive Filters (Year, Quarter, State, Transaction Type)  
- SQL Query Integration  
- Fraud Detection (99th percentile method)  
- Download Filtered Data  
- Dynamic Charts & Maps  

---

## 🖥️ Streamlit Dashboard

The dashboard provides:

- Real-time insights  
- Interactive visualizations  
- Multi-tab analysis:
  - Overview  
  - State Map  
  - District Map  
  - Top Insights  
  - Advanced Choropleth  
  - Future Scope  

---

## 🚀 Deployment

The project can be deployed using:

- Streamlit  

For Google Colab:
- Used Ngrok to generate public URL  

---

## 💡 Business Use Cases

- Customer Segmentation  
- Fraud Detection  
- Regional Analysis  
- Payment Trend Analysis  
- Marketing Optimization  
- Product Improvement  
- Insurance Insights  

---

## 🚨 Fraud Detection

- Implemented using **99th percentile threshold**  
- Identifies abnormal high-value transactions  
- Helps in risk management  

---

## 🔮 Future Scope

- Real-time data integration using APIs  
- Machine Learning for fraud detection  
- Advanced GeoJSON mapping  
- Customer segmentation (Clustering)  
- Predictive analytics  
- Cloud deployment (AWS)  
- Mobile-friendly dashboard  

---

## 🏁 Conclusion

This project demonstrates a complete **data analytics pipeline**, transforming raw JSON data into actionable insights through SQL and interactive dashboards.

It highlights strong skills in:
- Data Engineering (ETL)  
- Data Analysis (SQL + Python)  
- Data Visualization  
- Dashboard Development (Streamlit)  

---

## 📬 Contact

**Dharminder Singh Virk**  

---

⭐ If you like this project, don’t forget to give it a star!
