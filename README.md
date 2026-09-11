# Olist-Data-Analysis
# E-Commerce Performance & Customer Satisfaction Analysis

## 1. Project Overview

This project analyzes an e-commerce dataset to understand business performance, product category performance, delivery efficiency, customer satisfaction, and customer purchasing behavior.

The objective is to identify important business insights and provide actionable recommendations that can help management improve operational performance and customer experience.

---

## 2. Business Problem

The analysis focuses on understanding:

- Revenue and order trends over time
- Product category performance
- Delivery efficiency
- Customer satisfaction
- Repeat customer behavior

The main objective is to identify performance gaps and business opportunities using data.

---

## 3. Dataset

**Dataset:** Brazilian E-Commerce Public Dataset by Olist

The dataset contains multiple related datasets covering:

- Customers
- Orders
- Order Items
- Payments
- Reviews
- Products
- Sellers
- Geolocation
- Product Category Translation

The datasets were processed and combined where required for analysis.

---

## 4. Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab
- Google Sheets
- Looker Studio

---

## 5. Data Processing

The raw datasets were processed using Python and Pandas.

The processing included:

- Handling missing values
- Checking duplicate records
- Removing exact duplicate geolocation records
- Correcting data types
- Standardizing product categories
- Translating product category names
- Aggregating order-item data
- Aggregating payment data
- Aggregating review data
- Joining related datasets
- Creating calculated fields
- Checking unusual values

### Important Calculated Fields

- `delivery_days`
- `estimated_delivery_days`
- `delivery_delay_days`
- `delivery_status`
- `order_year`
- `order_month`
- `total_items`
- `total_product_value`
- `total_freight_value`
- `total_payment_value`

---

## 6. Business Questions

The analysis answers the following questions:

1. How does revenue and order volume change over time?
2. Which product categories generate the highest revenue and order volume?
3. How does delivery performance relate to customer satisfaction?
4. Are high-revenue categories also associated with high customer satisfaction?
5. What does customer purchasing behavior indicate about repeat purchases?

---

## 7. Key Findings

### 1. Delivery and Customer Satisfaction

Late orders had a substantially lower average review score compared with on-time orders.

- On-time orders: approximately 4.21 average rating
- Late orders: approximately 2.57 average rating

This indicates a strong association between delivery performance and customer satisfaction.

### 2. Revenue Concentration

A small number of product categories contribute a significant portion of total product revenue.

Health & Beauty, Watches & Gifts, and Bed/Bath/Table are among the major revenue-generating categories.

### 3. High Revenue Does Not Always Mean High Satisfaction

Some high-revenue product categories have relatively lower customer ratings.

This suggests that revenue performance should be evaluated together with customer experience.

### 4. Limited Repeat Purchasing

Only a relatively small proportion of unique customers placed multiple orders in the dataset.

This indicates a potential opportunity to improve customer retention.

### 5. Delivery Performance

A portion of delivered orders arrived after their estimated delivery date, creating an operational performance gap.

---

## 8. Recommendations

### Recommendation 1 — Improve Delivery Performance

Identify sellers, categories, and regions with high late-delivery rates and improve delivery monitoring.

**Success Metric:** On-time delivery percentage and average review score.

### Recommendation 2 — Improve High-Revenue/Low-Rating Categories

Investigate customer experience issues in high-revenue categories with relatively lower ratings.

**Success Metric:** Category-level revenue and average review score.

### Recommendation 3 — Improve Customer Retention

Introduce initiatives to encourage existing customers to make repeat purchases.

**Success Metric:** Repeat purchase rate and orders per customer.

---

## 9. Dashboard

An interactive Looker Studio dashboard was created to provide management with an overview of:

- Revenue
- Orders
- Average Review Score
- On-Time Delivery %
- Revenue trends
- Product category performance
- Delivery performance
- Customer satisfaction
- Repeat customer behavior

**Looker Studio Dashboard:**  
[Add your dashboard link here]

---

## 10. Project Files

| File | Description |
|---|---|
| `Olist_Data_Analysis.ipynb` | Complete Python analysis and data processing |
| `processed_olist_orders.csv` | Processed analysis-ready dataset |
| `README.md` | Project documentation |

---

## 11. Limitations

- The dataset is historical and may not represent current business performance.
- The dataset does not contain detailed cost/profit information.
- Missing delivery dates limit some delivery-related calculations.
- The analysis identifies associations but does not establish causation.

For example, the analysis shows that late delivery is associated with lower review scores, but it cannot prove that late delivery alone caused lower ratings.

---

## 12. Conclusion

The analysis indicates that delivery performance, product category performance, customer satisfaction, and customer retention are important areas for management attention.

Improving delivery reliability, addressing customer experience issues in important product categories, and increasing repeat purchases could provide opportunities to improve overall business performance.

---

## 13. AI Usage

AI tools were used during the assessment for:

- Understanding the dataset
- Developing and improving Python code
- Debugging errors
- Brainstorming analytical approaches
- Structuring business insights
- Improving documentation

AI-generated outputs were reviewed and verified against the actual dataset before being used in the analysis.
