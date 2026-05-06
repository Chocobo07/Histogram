# 📊 Malicious IP Analysis with Python

This project analyzes a dataset of **200 malicious IP addresses** and visualizes their characteristics using Python.

---

## 📁 Dataset Overview

The dataset contains IPs reported for suspicious activities such as:

* Port scanning
* Brute force attacks
* Botnet activity
* Data exfiltration

### 📌 Features Included

* **IP Address**
* **ASN (Autonomous System Number)**
* **Country**
* **Reputation Score**

---

## 🚀 Features of the Project

* 📊 Histogram of reputation scores
* 🌍 Distribution of malicious IPs by country
* 🏢 Top networks (ASN) associated with malicious activity

---

## 🧠 How the Code Works

1. Load the dataset using `pandas`
2. Preview the data to check structure
3. Create a histogram to analyze risk levels
4. Generate bar charts for:

   * Country distribution
   * ASN distribution

---

## 🛠️ Requirements

Install the required libraries:

```bash
pip install pandas matplotlib
```

---

## ▶️ How to Run

1. Place the dataset in the same folder as the script
2. Run the Python file:

```bash
python histogram.py
```

---

## 📊 Output

The program generates:

### 1. Reputation Score Histogram

Shows how malicious IPs are distributed based on risk level.

### 2. Country Distribution Chart

Displays which countries have the highest number of malicious IPs.

### 3. ASN Distribution Chart

Highlights the top 10 networks associated with malicious IP activity.

---

## 📌 Example Use Cases

* Cybersecurity analysis
* Threat intelligence visualization
* Academic projects
* Data analysis practice

---

## ⚠️ Notes

* Ensure column names match the dataset:

  * `Reputation_Score`
  * `Country`
  * `ASN`
* You can modify the number of bins in the histogram for better visualization.

---

