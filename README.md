# 🛒 Customer Purchase Behaviour — Exploratory Data Analysis

A complete end-to-end EDA on a retail customer dataset to uncover purchasing patterns, segment customers, and deliver actionable business recommendations.

---

## 📌 Overview

Retail businesses struggle to identify *who* their most valuable customers are, *what* they buy, and *where* growth opportunities lie. This project digs into customer demographic and purchase data to answer those questions with data-backed evidence.

**Key questions answered:**
- What does the typical customer profile look like (age, gender, education, region)?
- Which regions and product categories drive the most revenue?
- Do loyalty programmes actually increase spending behaviour?
- Can we cluster customers into meaningful, actionable segments?

---

## 📊 What's Inside the Notebook

| Section | Description |
|---|---|
| **1. Data Cleaning** | Missing value audit, duplicate removal, IQR outlier detection, categorical consistency checks |
| **2. Univariate Analysis** | Age & purchase amount distributions with mean/median markers, all categorical breakdowns |
| **3. Bivariate Analysis** | Revenue by region, category, loyalty tier, gender, and education |
| **4. Age vs Spend** | Scatter plot with trend line, average spend by age group |
| **5. Correlation Heatmap** | Full feature correlation matrix with encoded categoricals |
| **6. Customer Segmentation** | K-Means clustering (elbow method + K=3) with segment profiles |
| **7. Pareto Analysis** | Revenue concentration — do top 20% of customers drive 80% of revenue? |
| **8. Business Recommendations** | 5 actionable insights written in non-technical language |

---

## 🛠️ Tech Stack

- **Python 3.10**
- **Pandas & NumPy** — data manipulation and cleaning
- **Matplotlib & Seaborn** — visualisations
- **Scikit-learn** — K-Means clustering, label encoding, standard scaling

---

## 📁 Dataset

The dataset contains customer purchase records with the following features:

| Column | Description |
|---|---|
| `age` | Customer age |
| `gender` | Male / Female |
| `region` | North / South / East / West |
| `education` | Education level |
| `product_category` | Type of product purchased |
| `purchase_amount` | Transaction value (₹) |
| `purchase_frequency` | How often the customer buys |
| `loyalty_status` | Gold / Silver / Regular |

---

## 🚀 How to Run

**Option 1 — Google Colab (recommended)**
1. Upload `Customer_Sales_EDA.ipynb` to [Google Drive](https://drive.google.com)
2. Right-click → **Open with → Google Colaboratory**
3. Upload `customer_data.csv` using the folder icon in the left sidebar
4. Run all cells: **Runtime → Run all**

**Option 2 — Local (Jupyter)**
```bash
git clone https://github.com/AaryanGupta01/Customer-Sales-EDA
cd Customer-Sales-EDA
pip install pandas numpy matplotlib seaborn scikit-learn
jupyter notebook Customer_Sales_EDA.ipynb
```

---

## 💡 Key Findings

- **Regional revenue** is driven by customer volume, not higher per-customer spend — acquisition campaigns in underrepresented regions would be high-ROI
- **Loyalty programme** rewards existing high spenders rather than changing behaviour — a spend-linked reward structure would be more effective
- **K-Means clustering** revealed 3 distinct customer segments, each requiring a different retention/acquisition strategy
- **Top 20% of customers** contribute a disproportionate share of total revenue — confirming the Pareto principle holds in this dataset

---

## 📂 Repository Structure

```
Customer-Sales-EDA/
│
├── Customer_Sales_EDA.ipynb   # Main analysis notebook
├── customer_data.csv          # Dataset
└── README.md                  # This file
```

---

## 👤 Author

**Aaryan Gupta**  
B.Tech CSE (Data Science) — Vellore Institute of Technology  
[![GitHub](https://img.shields.io/badge/GitHub-AaryanGupta01-181717?logo=github)](https://github.com/AaryanGupta01)
