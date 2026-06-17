# E-Commerce Customer Analytics

An end-to-end exploratory data analysis project using the Brazilian Olist E-Commerce dataset. The goal of this project is to understand customer behavior, purchasing patterns, revenue trends, and retention through a series of analyses and visualizations.

---

## Dataset

This project uses the **Brazilian E-Commerce Public Dataset by Olist**.

Dataset Link:

https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce

The dataset contains information on:

* Customers
* Orders
* Order Items
* Payments
* Products
* Reviews
* Sellers
* Geolocation

---

## Repository Structure

```text
ecommerce-customer-analytics/
│
├── data/
│   ├── raw/
│   └── results/
│
├── notebooks/
│   ├── 01_get_data.ipynb
│   ├── 02_eda_and_data_cleaning.ipynb
│   ├── 03_rfm_analysis.ipynb
│   ├── 04_cohort_analysis.ipynb
│   ├── 05_revenue_analysis.ipynb
│   └── 06_final_insights.ipynb
│
├── README.md
└── .gitignore
```

---

## Project Objectives

* Perform exploratory data analysis on a real-world e-commerce dataset.
* Understand customer purchase behavior.
* Analyze order trends and seasonality.
* Study payment and delivery patterns.
* Segment customers using RFM analysis.
* Perform cohort analysis and retention analysis.
* Understand revenue concentration and category performance.
* Generate actionable business insights.

---

## Analyses Covered

### Exploratory Data Analysis

* Missing values
* Duplicate records
* Order status distribution
* Payment analysis
* Delivery performance
* Product category analysis
* Correlation analysis

### Customer Segmentation

* Recency
* Frequency
* Monetary value
* RFM scores
* Customer segments

### Cohort Analysis

* Monthly cohorts
* Retention heatmaps
* Customer retention curves

### Revenue Analysis

* Revenue trends
* Category contribution
* Seasonality
* Pareto analysis

### Advanced Visualizations

* Correlation heatmaps
* ECDF plots
* Violin plots
* Treemaps
* Revenue heatmaps
* Sankey diagrams
* Geographic analysis

---

## Setup

Clone the repository:

```bash
git clone https://github.com/<your_username>/ecommerce-customer-analytics.git
```

Move into the project directory:

```bash
cd ecommerce-customer-analytics
```

---

## Download the Dataset

Download the Olist dataset from Kaggle and place all CSV files inside:

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

## Notebook Sequence

### 01_get_data.ipynb

Load and inspect the raw datasets.

### 02_eda_and_data_cleaning.ipynb

Perform exploratory data analysis and create the analytical dataset.

### 03_rfm_analysis.ipynb

Segment customers using the RFM framework.

### 04_cohort_analysis.ipynb

Analyze customer retention across cohorts.

### 05_revenue_analysis.ipynb

Study revenue trends and category performance.

### 06_final_insights.ipynb

Summarize findings and provide business recommendations.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Plotly
* Jupyter Notebook

---

## Key Skills Demonstrated

* Exploratory Data Analysis
* Data Cleaning
* Feature Engineering
* Customer Analytics
* Cohort Analysis
* Retention Analysis
* Data Visualization
* Business Insights

---

## Future Enhancements

* Customer Lifetime Value (CLV) modeling
* Churn prediction
* Recommendation systems
* Interactive dashboards
* Streamlit application

---

## License

This project is intended for educational and portfolio purposes.
