# E-Commerce Retail Analytics Project

## Overview

- Includes:
  - Data cleaning  
  - SQL-based querying  
  - RFM customer segmentation  
  - Cohort retention analysis  
  - Discount impact assessment  
  - Interactive BI dashboard

---

## Key Insights

- Total revenue of **~£17.4M** was generated across **36.9K orders** over two years.

- Peak monthly revenue of **~£1.17M** occurred in **November 2010**.

- Revenue by country (Total: 41 countries):
  - United Kingdom: **~£14.4M (~82.8%)**
  - EIRE: ~£616K  
  - Netherlands: ~£554K  
  - Germany: ~£425K  

- Top products by revenue:
  - REGENCY CAKESTAND 3 TIER: **~£277.7K**
  - WHITE HANGING HEART T-LIGHT HOLDER: **~£247.0K**
  - PAPER CRAFT, LITTLE BIRDIE: **~£168.5K**

- Customer segmentation (Total customers: 5,878):
  - High Value: **2,375**
  - Low Value: **1,912**
  - Mid Value: **1,591**

- Month-1 retention is **~35%**.
 
- Discount impact:
  - High Discount: **~£8.44M revenue**
  - Heavy Discount: **~4.54M units, ~£2.19M revenue**

- The **"General" category contributes the highest sales**, with other categories significantly lower.

---

## Tools & Technologies

- Python
- SQLite
- Jupyter Notebook
- Tableau
- Excel

---

## Dataset

| Field | Details |
|-------|--------|
| Name | Online Retail II |
| Source | UCI Machine Learning Repository |
| Dataset Link | https://archive.ics.uci.edu/dataset/502/online+retail+ii |
| File | online_retail_II.xlsx |

---

## Dashboard

- Visualizes:
    - Revenue by country (map) 
    - Monthly category trends (line chart)  
    - Customer segments (bar chart)

- Highlights:
    - UK dominance  
    - Q4 revenue spike  
    - "General" category dominance  
    - Customer segment distribution 

---

## How to Run

### Prerequisites
- Python 3.8+
- Jupyter Notebook

### Steps

#### 1. Clone the repository
```bash
git clone https://github.com/Chaitraashree-C31/ecommerce-sales-performance-analysis.git
cd ecommerce-retail-analytics
```

#### 2. Launch the notebook
jupyter notebook -> ecommerce_analysis.ipynb
