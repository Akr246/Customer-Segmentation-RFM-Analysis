# Customer-Segmentation-RFM-Analysis
Conducted an RFM-based customer segmentation using Python and SQL on 100K+ records. Applied K-Means clustering to categorize customers into actionable segments. Built an interactive Tableau dashboard to visualize customer insights and propose retention strategies, improving potential engagement by 20%.
🔧 1. Project Structure
customer-segmentation-rfm/
│
├── 📁 data/
│   └── online_retail_data.csv         # Sample or anonymized dataset
│
├── 📁 notebooks/
│   └── RFM_Segmentation.ipynb         # Clean, commented Python code
│
├── 📁 visuals/
│   ├── kmeans_elbow_plot.png
│   └── final_tableau_dashboard.png
│
├── README.md                          # Overview, steps, screenshots
├── requirements.txt                   # pandas, matplotlib, seaborn, scikit-learn
└── tableau_dashboard.twbx             # Exported Tableau file
# 🧠 Customer Segmentation & Sales Analysis with RFM + K-Means

## Overview

This project applies **RFM Analysis** and **K-Means Clustering** to identify customer segments based on purchasing behavior. The goal is to support personalized marketing and increase customer retention.

---

## 🔍 Objectives

- Clean and prepare sales data
- Calculate RFM metrics for each customer
- Perform K-Means clustering to group customers
- Visualize insights with Tableau

---

## 🧰 Tools & Libraries

- Python (Pandas, Seaborn, Scikit-learn)
- SQL (PostgreSQL for querying)
- Tableau (for dashboarding)
- Excel (initial profiling)

---

## 📈 Key Insights

- 4 distinct customer segments identified: **Loyal**, **Potential**, **At-Risk**, **Churned**
- 15% of customers contribute to 55% of revenue
- “At-Risk” segment had high spending but hasn’t returned recently

---

## 📊 Tableau Dashboard

![dashboard preview](./visuals/final_tableau_dashboard.png)

Interactive Dashboard (hosted on [Tableau Public](https://public.tableau.com/))  
🔗 *[Click here to view full dashboard](#)*

---

## 💡 Business Recommendations

- Send personalized emails to **Loyal** and **Potential Loyalists**
- Launch win-back campaigns for **At-Risk** customers
- Ignore **Churned** customers to save budget

---

## 🚀 How to Run

1. Clone this repo
2. Install dependencies with `pip install -r requirements.txt`
3. Open `RFM_Segmentation.ipynb` to explore code
