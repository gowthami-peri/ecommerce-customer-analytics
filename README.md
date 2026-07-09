<img width="890" height="470" alt="image" src="https://github.com/user-attachments/assets/626e432f-c906-4c09-be4c-44a8ec15d069" />

<img width="1075" height="701" alt="image" src="https://github.com/user-attachments/assets/57bfacac-769e-4c69-8b37-fb1008d6ffae" />

<img width="767" height="790" alt="image" src="https://github.com/user-attachments/assets/3b4a5a3d-5a9d-4736-a4a0-c79a0f16690a" />

<img width="928" height="547" alt="image" src="https://github.com/user-attachments/assets/94c47c97-21a6-437d-a89f-3165155cabfe" />


# E-Commerce Customer Analytics

An end-to-end customer analytics case study using the **Brazilian Olist E-Commerce Dataset**. This project demonstrates how raw transactional data can be transformed into actionable business insights through exploratory data analysis, customer segmentation, operational analysis, and revenue analytics.

The project follows a typical business analytics workflow—from data preparation and cleaning to executive-level recommendations—and showcases techniques commonly used by data analysts and data scientists.

---

## Dataset

This project uses the **Brazilian E-Commerce Public Dataset by Olist**.

**Dataset Link**

https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce

The dataset contains information about:

- Customers
- Orders
- Order Items
- Products
- Payments
- Reviews
- Sellers
- Geolocation

---

# Project Workflow

```text
Raw Olist Data
        │
        ▼
Data Preparation
        │
        ▼
Exploratory Data Analysis
        │
        ▼
Customer Segmentation (RFM)
        │
        ▼
Customer Behavior & Operations
        │
        ▼
Revenue & Product Analytics
        │
        ▼
Business Recommendations
```

---

# Repository Structure

```text
ecommerce-customer-analytics/
│
├── data/
│   ├── raw/
│   │   └── README.md
│   │
│   └── results/
│       ├── customer_analytics.parquet
│       ├── customer_rfm.parquet
│       └── rfm_segment_summary.csv
│
├── notebooks/
│   ├── 01_get_data.ipynb
│   ├── 02_exploratory_data_analysis.ipynb
│   ├── 03_rfm_analysis.ipynb
│   ├── 04_customer_behavior_and_operations.ipynb
│   └── 05_revenue_and_product_analytics.ipynb
│
├── README.md
└── .gitignore
```

---

# What This Project Explores

This project answers several business questions, including:

- How has revenue changed over time?
- Which product categories drive business performance?
- Who are the highest-value customers?
- How can customers be segmented using RFM analysis?
- How do delivery performance and customer reviews relate?
- What payment methods do customers prefer?
- How concentrated is revenue among customers?
- What business recommendations can be derived from the data?

---

# Notebook Overview

## 01 – Data Preparation

- Load raw Olist datasets
- Validate data quality
- Merge multiple tables into an analytical dataset
- Export cleaned datasets for downstream analysis

---

## 02 – Exploratory Data Analysis

- Customer overview
- Order trends
- Product analysis
- Payment analysis
- Delivery analysis
- Missing value analysis
- Summary statistics

---

## 03 – Customer Segmentation (RFM)

- Recency, Frequency, Monetary analysis
- Customer scoring
- Customer segmentation
- Revenue contribution by segment
- Customer behavior analysis

---

## 04 – Customer Behavior & Operations

- Purchase timing analysis
- Delivery performance
- Customer review analysis
- Operational insights
- Delivery and customer satisfaction

---

## 05 – Revenue & Product Analytics

- Monthly revenue trends
- Product category performance
- Payment behavior
- Pareto analysis
- Executive summary
- Business recommendations

---

# Key Visualizations

The project includes a variety of business-focused visualizations, including:

- Customer purchase distributions
- Correlation heatmaps
- RFM customer segmentation
- Revenue trends
- Product portfolio bubble chart
- Payment method distribution
- Delivery performance analysis
- Customer review analysis
- Pareto analysis of customer revenue

---

# Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- PyArrow
- Jupyter Notebook

---

# Skills Demonstrated

- Exploratory Data Analysis (EDA)
- Data Cleaning & Transformation
- Feature Engineering
- Customer Analytics
- Customer Segmentation (RFM)
- Revenue Analytics
- Product Analytics
- Business Analytics
- Data Visualization
- Executive Reporting

---

# Setup

## Clone the repository

```bash
git clone https://github.com/<your_username>/ecommerce-customer-analytics.git
```

Move into the project directory.

```bash
cd ecommerce-customer-analytics
```

---

## Install dependencies

```bash
pip install -r requirements.txt
```

---

## Download the Dataset

Download the Olist dataset from Kaggle and place the CSV files inside:

```text
data/raw/
```

Expected files:

```text
olist_customers_dataset.csv
olist_orders_dataset.csv
olist_order_items_dataset.csv
olist_order_payments_dataset.csv
olist_order_reviews_dataset.csv
olist_products_dataset.csv
olist_sellers_dataset.csv
olist_geolocation_dataset.csv
product_category_name_translation.csv
```

---

## Run the Notebooks

Execute the notebooks in the following order:

1. 01_get_data.ipynb
2. 02_exploratory_data_analysis.ipynb
3. 03_rfm_analysis.ipynb
4. 04_customer_behavior_and_operations.ipynb
5. 05_revenue_and_product_analytics.ipynb

---

# Potential Extensions

This project can be extended with:

- Customer Lifetime Value (CLV) prediction
- Customer churn prediction
- Product recommendation systems
- Sales forecasting
- Interactive dashboards (Streamlit or Power BI)

---

# License

This project is intended for educational and portfolio purposes.
