# 📊 Malicious IP Data Analysis (Histogram & Distribution Study)

## 📌 Overview
This project analyzes a dataset of malicious IP addresses to visualize patterns in:
- Reputation scores
- Country distribution
- ASN (Autonomous System Numbers)
- Risk level comparison

It uses histogram-based visualizations similar to statistical distribution analysis (normal curves and grouped comparisons).

---

## 📁 Dataset
The dataset used is:

4_malicious_ips.csv

It contains:
- IP addresses
- Reputation scores (risk level)
- Country of origin
- ASN (network identifier)

---

## ⚙️ Technologies Used

- Pandas → data loading and processing  
- NumPy → mathematical computations  
- Matplotlib → data visualization  

---

## 📌 Features

### 1. 📈 Reputation Score Distribution
- Histogram of malicious IP reputation scores  
- Includes a normal distribution curve overlay  
- Helps identify if data is skewed or normally distributed  

### 2. 🌍 Top 10 Countries with Malicious IPs
- Bar chart showing countries with the most malicious IPs  
- Helps identify geographic sources of cyber threats  

### 3. 🖧 Top 10 ASNs
- Shows most common Autonomous System Numbers involved  
- Identifies suspicious or frequently abused networks  

### 4. ⚖️ Risk Level Comparison
- Splits IPs into:
  - Low Risk (below median reputation score)
  - High Risk (above median reputation score)
- Displays overlapping histograms for comparison  

---

## ▶️ How to Run the Project

### 1. Install dependencies
pip install pandas numpy matplotlib

### 2. Run the script
python your_script_name.py

Make sure the dataset path is correct before running.

---

## 📂 Workflow Summary

1. Load dataset using Pandas  
2. Extract and clean reputation scores  
3. Plot histogram with normal curve  
4. Visualize top countries (bar chart)  
5. Visualize top ASNs (bar chart)  
6. Compare low-risk vs high-risk IPs  

---

## 📊 Output Visualizations

- 📊 Reputation Score Histogram + Normal Curve  
- 🌍 Top 10 Countries Bar Chart  
- 🖧 Top 10 ASN Bar Chart  
- ⚖️ Risk Level Comparison Histogram  

---

## 📌 Key Insights

- Shows distribution of malicious IP risk levels  
- Identifies countries with highest malicious activity  
- Reveals networks (ASNs) linked to attacks  
- Separates IPs into risk categories for deeper analysis  

---

## 🚀 Possible Improvements

- Add world map visualization of IP locations  
- Include time-based attack trend analysis  
- Apply machine learning for anomaly detection  
- Build interactive dashboard (Plotly / Power BI)  
- Perform clustering of malicious behavior patterns  
