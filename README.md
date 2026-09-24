# RetailPulse 360 — Sales, Profit & Customer Intelligence

A Python-based retail analytics project developed for the **MainCrafts Technology 2-Day Skill Certification Program – Data Science & Data Analytics Using Python**.

The project analyzes Superstore retail transaction data to identify sales and profitability patterns, customer behavior, product performance, regional differences, discount effects, shipping trends, and actionable business opportunities.

---

## 📌 Project Overview

Retail businesses generate large amounts of transactional data, but raw data alone does not provide clear business direction.

**RetailPulse 360** converts retail transaction data into meaningful business insights through:

- Data cleaning and preparation
- Exploratory Data Analysis (EDA)
- KPI analysis
- Sales and profit analysis
- Product and category analysis
- Regional analysis
- Customer and segment analysis
- Discount and profitability analysis
- Time-series analysis
- Shipping analysis
- Business question analysis
- Evidence-based recommendations

The goal is to move from **raw transactional data → analysis → insights → business decisions**.

---

## 🎯 Objectives

1. Understand overall sales and profitability performance.
2. Identify high-performing and low-performing products and categories.
3. Compare performance across regions.
4. Analyze customer segments and purchasing behavior.
5. Examine the relationship between discounts and profit.
6. Identify important sales and profit trends over time.
7. Analyze shipping patterns and their business implications.
8. Convert analytical findings into practical business recommendations.

---

## 📊 Dataset

The project uses a **Superstore retail transaction dataset** containing information related to:

- Orders
- Customers
- Products
- Categories
- Regions
- Sales
- Profit
- Discounts
- Shipping
- Customer segments
- Order dates

**Dataset file:** `superstore.csv`

---

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Data analysis and processing |
| Pandas | Data manipulation |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| Jupyter Notebook | Analysis workflow |
| Streamlit | Interactive dashboard |
| GitHub | Project version control |

---

## 🔄 Project Workflow

```text
Raw Dataset
     ↓
Data Inspection
     ↓
Data Cleaning
     ↓
Feature Engineering
     ↓
Exploratory Data Analysis
     ↓
KPI Analysis
     ↓
Sales & Profit Analysis
     ↓
Customer / Product / Regional Analysis
     ↓
Business Questions
     ↓
Key Findings
     ↓
Recommendations
```

---

## 📈 Key Analysis Areas

### Executive KPIs

- Total Sales
- Total Profit
- Total Orders
- Average Order Value
- Profit Margin

### Sales & Profitability

The project analyzes sales and profit across products, categories, regions, customer segments, and time.

### Customer Analysis

Customer contribution and segment-level purchasing patterns are examined to identify important customer groups.

### Discount Analysis

The project examines the relationship between discounts and profitability.

> Correlation is treated as an association and not as proof of causation.

### Time-Series Analysis

Sales and profit trends are analyzed over time to identify stronger and weaker periods.

### Shipping Analysis

Shipping patterns are analyzed to understand their relationship with orders and business performance.

---

## ❓ Business Questions

The analysis addresses practical questions such as:

- Which categories generate the most sales?
- Which categories generate the most profit?
- Which products are loss-making?
- Which regions perform strongly or weakly?
- Which customer segments contribute most to the business?
- Does higher discounting relate to lower profitability?
- What periods show stronger sales performance?
- Which areas require management attention?

---

## 💡 Key Insights

The project identifies patterns across:

- Sales performance
- Profitability
- Product performance
- Regional performance
- Customer segments
- Discount behavior
- Time-based trends
- Shipping performance

Detailed findings and supporting visualizations are available in the project report and notebook.

---

## 🚀 Business Recommendations

Based on the analysis, the project provides evidence-based recommendations including:

1. Review and optimize discount strategies where discounting is associated with weaker profitability.
2. Investigate loss-making products and improve their pricing, cost structure, or promotional strategy.
3. Focus on improving weaker product/category performance.
4. Investigate regional performance differences and identify operational or market-specific factors.
5. Strengthen customer retention and segment-specific strategies using customer contribution insights.

These recommendations are based on the analyzed dataset and should be validated against operational information before implementation.

---

## 📂 Project Structure

```text
RetailPulse360/
│
├── README.md
├── RetailPulse360_Chirag.ipynb
├── superstore.csv
├── RetailPulse360_Report_Chirag.pdf
├── requirements.txt
│
└── visuals/
    ├── data_overview.png
    ├── cleaning.png
    ├── analysis.png
    └── dashboard.png
```

---

## ▶️ How to Run

### 1. Clone the repository

```bash
git clone <YOUR_GITHUB_REPOSITORY_URL>
cd RetailPulse360
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Open the notebook

```bash
jupyter notebook
```

Open:

```text
RetailPulse360_Chirag.ipynb
```

Run the notebook cells sequentially.

---

## 📊 Dashboard

The project can be presented through an interactive dashboard showing:

- KPIs
- Sales trends
- Profit trends
- Product performance
- Regional performance
- Customer segments
- Business recommendations

Dashboard screenshots are included in the `visuals/` folder where applicable.

---

## 📄 Project Report

The complete project documentation is available in:

`RetailPulse360_Report_Chirag.pdf`

The report contains:

- Problem statement
- Objectives
- Dataset description
- Methodology
- Data preparation
- Exploratory analysis
- Visualizations
- Key findings
- Business recommendations
- Limitations
- Conclusion

---

## ⚠️ Limitations

The analysis is based on the available transaction dataset.

The dataset does not necessarily capture all real-world business factors such as:

- Operational costs
- Inventory constraints
- Competitor pricing
- Marketing expenditure
- Store-level operational conditions
- External market conditions

Therefore, analytical relationships should be interpreted within the scope of the available data.

---

## 👤 Author

**Chirag Chhabra**

Data Science & Data Analytics Project  
MainCrafts Technology 2-Day Skill Certification Program

---

## 📜 Program

**MainCrafts Technology**

**Domain:** Data Science & Data Analytics Using Python

