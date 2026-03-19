# 📊 Deep-Dive Analysis & Interactive Dashboard (RFM-Based Customer Segmentation)

## 📌 Project Overview

This project focuses on solving complex business problems using **data-driven analysis and interactive dashboarding**. The main objective is to analyze customer behavior and generate actionable insights using **RFM (Recency, Frequency, Monetary) segmentation**.

---

## 🎯 Objectives

* Define key business KPIs
* Perform deep-dive analysis on customer data
* Segment customers using RFM model
* Build an interactive dashboard for business insights

---

## 📊 Core KPIs

| KPI                           | Description                                   |
| ----------------------------- | --------------------------------------------- |
| **Total Sales**               | Total revenue generated from all transactions |
| **Total Orders**              | Number of unique orders                       |
| **Average Order Value (AOV)** | Revenue per order                             |
| **Unique Customers**          | Total distinct customers                      |

---

## 🧠 Deep-Dive Analysis: RFM Segmentation

### 🔍 What is RFM?

RFM stands for:

* **Recency** – How recently a customer purchased
* **Frequency** – How often they purchase
* **Monetary** – How much they spend

Each customer is scored (1–5) and segmented accordingly.

---

## 👥 Customer Segments

| Segment                | Count | Description                                   |
| ---------------------- | ----- | --------------------------------------------- |
| 🟢 **Champions**       | 20    | Best customers (high value, frequent, recent) |
| 🔵 **Loyal Customers** | 246   | Frequent and consistent buyers                |
| 🟡 **Big Spenders**    | 106   | High spending customers                       |
| 🔴 **At Risk**         | 146   | Customers likely to churn                     |
| ⚪ **Others**           | 147   | Moderate/low engagement                       |

---

## 🔑 Key Insights

* Loyal customers (246) form the **largest valuable segment**
* 146 customers are at risk and need **re-engagement strategies**
* Champions are small in number but contribute **high revenue**
* Segmentation enables **targeted marketing and personalization**

---

## 📊 Tools & Technologies Used

* **Python (Pandas, NumPy, Matplotlib)**
* **Jupyter Notebook**
* **Power BI / Tableau (Dashboard)**
* **GitHub (Version Control)**

---

## 📁 Project Structure

```
├── Cleaned_DataSet.csv       # Input dataset
├── RFM_Output.csv            # Processed RFM data
├── rfm_analysis.py / notebook
├── dashboard.pbix (optional)
├── README.md
```

---

## ⚙️ How to Run the Project

1. Clone the repository:

```
git clone https://github.com/your-username/your-repo-name.git
```

2. Install dependencies:

```
pip install pandas numpy matplotlib
```

3. Run the Python script or notebook:

```
python rfm_analysis.py
```

4. Output:

* `RFM_Output.csv` will be generated
* Use this file in Power BI for dashboard

---

## 📈 Dashboard Features

* KPI Overview (Sales, Orders, AOV, Customers)
* Customer Segmentation (RFM)
* Revenue Distribution by Segment
* Interactive Filters (Date, Segment, Category)

---

## 🚀 Business Impact

* Identifies high-value customers
* Detects churn risk early
* Enables targeted marketing campaigns
* Improves customer retention and revenue

---

## 🧾 Conclusion

This project demonstrates how RFM segmentation can transform raw data into meaningful business insights, helping organizations make informed decisions and improve customer engagement.

---

## 📌 Author

**Vishnu**
B.Tech (AI & ML)

---
