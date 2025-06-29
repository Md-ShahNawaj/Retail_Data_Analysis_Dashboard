# Retail Data Analysis Dashboard

An excel dashboard project analyzing customer behavior and sales performance using the [UCI Online Retail II dataset](https://archive.ics.uci.edu/ml/datasets/Online+Retail+II). This project uncovers key insights into customer segmentation, churn, order behavior, and regional sales distribution.

---

## Dashboard Overview

![Retail Dashboard](Retail_Data_Analysis_Dashboard.png)

## Dashboard Features Explained

- **Total Turnover: $17.74M (2009–2011)**  
  Total revenue generated from all customer purchases over three years.

- **Customer Lifetime Value Segmentation**  
  Customers are categorized into Low, Medium, and High value groups based on their total spending.

- **New & Churned Customers by Month**  
  Visualizes monthly trends in new customer acquisition and customer loss (churn).

- **Monthly Orders and Seasonal Trends**  
  Shows fluctuations in order volume across months to identify peak seasons and slow periods.

- **Top Countries by Revenue**  
  Highlights the countries that generated the most revenue, helping identify key markets.

### Key Performance Metrics

- **Total Customers:** 5,881  
  Number of unique customers who placed at least one order.

- **Total Orders:** 36,975  
  Total number of purchase transactions.

- **Average Orders per Customer:** 6  
  On average, each customer placed 6 orders.

- **Average Order Value:** $480  
  The average revenue from a single transaction.

- **Average Revenue per Customer:** $3,017  
  On average, each customer contributed $3,017 in total revenue.

## Key Insights

1.  **Highest revenue** recorded in 2011 ($8.34M).
2.  **Customer acquisition** peaked in Dec 2009 (955 new customers).
3.  **Customer churn** saw a major rise in late 2011.
4.  **United Kingdom** contributed over 80% of the revenue.
5.  **Low CLV segment** (53%) should be targeted with upselling/cross-selling strategies.
6.  **Monthly monitoring** helps track customer lifecycle stages effectively.

---

##  Recommendations

- **Focus on High CLV Segments:**  
  Target medium and high-value customers with personalized promotions and loyalty programs.

- **Upsell to Low CLV Customers:**  
  Encourage low-value customers to increase order size through bundle deals or product suggestions.

- **Monitor Customer Churn Regularly:**  
  Investigate churn spikes and implement retention strategies such as win-back campaigns.

- **Prepare for Seasonal Demand:**  
  Use seasonal patterns to optimize inventory and marketing during peak months.

- **Invest in Top-Performing Regions:**  
  Focus efforts on markets like the UK, which generate most of the revenue.

- **Track KPIs Continuously:**  
  Use dashboards for ongoing monitoring and strategy refinement.

---

##  Dataset

- **Source:** [UCI Machine Learning Repository – Online Retail II](https://archive.ics.uci.edu/ml/datasets/Online+Retail+II)
- **File Used:** `online_retail_II_raw_data.xlsx`

---

## Tools & Techniques Used

- **Tool:** Microsoft Excel  
- **Techniques:**  
  - Data Cleaning  
  - Pivot Tables  
  - Interactive Charts (Pie, Bar, Line)  
  - Dashboard Design  
  - Data Analysis & Interpretation
  -  **Power Query**
  -   **Excel Formulas (Count, CountA, If, Ifs, Sum, Xlookup, Unique)**

---

## Repository Structure

```bash
Retail-Data-Analysis-Dashboard/
│
├── Retail_Data_Analysis_Dashboard.png         # Final dashboard image
├── retail_data_analysis_dashboard.xlsx        # Processed dashboard file
├── online_retail_II_raw_data.xlsx             # Original dataset
└── README.md                                  # This file
