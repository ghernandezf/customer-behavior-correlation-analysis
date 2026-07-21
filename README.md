# 📊 Customer Behavior Correlation Analysis

## 📌 Project Overview

This project analyzes customer behavior data from **NovaRetail+**, a fictional e-commerce platform operating in Latin America.

The objective is to identify which customer behavior variables are most strongly associated with **annual revenue**, using multiple correlation techniques and exploratory data analysis (EDA). The project emphasizes responsible interpretation of statistical relationships, avoiding causal conclusions.

---

## 🎯 Business Problem

The Growth and Retention team at NovaRetail+ wants to answer the following question:

> **Which customer behaviors are most strongly associated with annual revenue generated?**

The analysis aims to provide insights that can support future marketing strategies, customer retention initiatives, and business decision-making.

---

## 🛠️ Tools & Technologies

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 📂 Dataset

The dataset contains **15,000 customer records** from 2024 and includes demographic, behavioral, marketing, and revenue information.

Main variables include:

- Age
- Estimated income
- Monthly visits
- Monthly purchases
- Targeted advertising spend
- Customer satisfaction
- Premium membership
- Churn status
- Device type
- Region
- Annual revenue

---

## 🔍 Analysis Workflow

1. Data exploration
2. Data quality validation
3. Descriptive statistics
4. Correlation analysis
   - Pearson
   - Point-Biserial
   - Cramér's V
5. Data visualization
6. Business interpretation
7. Limitations and recommendations

---

## 📈 Key Findings

### ✅ Monthly purchases show the strongest relationship with annual revenue

- Pearson correlation: **0.97**
- Customers who purchase more frequently tend to generate significantly higher annual revenue.

### ✅ Advertising spend is moderately associated with customer visits

- Pearson correlation: **0.58**
- Higher advertising investment is associated with more customer visits, although not necessarily with higher revenue.

### ✅ Customer characteristics explain little of the revenue variability

Premium membership, churn status, device type, and region showed weak or negligible statistical associations with annual revenue.

---

## 💼 Business Recommendations

- Focus business strategies on increasing purchase frequency rather than only increasing website traffic.
- Evaluate advertising effectiveness through controlled A/B experiments.
- Develop predictive models to better understand customer value.
- Perform segmented analyses by customer groups to identify additional opportunities.

---

## ⚠️ Limitations

- Correlation does not imply causation.
- The analysis is based on a single dataset from 2024.
- External factors affecting customer behavior were not included.
- Results should be validated using additional analytical techniques and future datasets.

---

## 📷 Project Visualizations

### Correlation Heatmap

*(Insert heatmap image here)*

### Monthly Purchases vs Annual Revenue

*(Insert scatterplot here)*

### Advertising Spend vs Annual Revenue

*(Insert scatterplot here)*

---

## 📁 Repository Structure

```
customer-behavior-correlation-analysis/
│
├── data/
│   └── novaretail_comportamiento_clientes_2024.csv
│
├── images/
│   ├── correlation_heatmap.png
│   ├── purchases_vs_revenue.png
│   └── advertising_vs_revenue.png
│
├── notebook.ipynb
├── requirements.txt
└── README.md
```

---

## 🚀 How to Run

Clone the repository:

```bash
git clone https://github.com/yourusername/customer-behavior-correlation-analysis.git
```

Install the required packages:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open the notebook and run all cells.

---

## 👨‍💻 Author

**Gabriel Hernández**

Transitioning from Chemistry to Data Analytics.

- SQL
- Python
- Power BI
- Excel
- Exploratory Data Analysis
- Statistical Analysis
- Data Visualization
