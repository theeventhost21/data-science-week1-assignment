## 1. Title and Objective
- Title: E-Commerce Sales Analysis & Dashboard 
- Objective: The goal is to clean transactional data (ecommerce_data.csv), analyze key performance indicators (KPIs), visualize sales trends, and present a professional single-page dashboard mockup.

## 2. Dataset Overview
- Dataset Name: ecommerce_data.csv
- Description: Contains e-commerce transaction details including order IDs, product categories, quantities sold, prices, payment methods, and timestamps.

## 3. Cleaning Summary
- Checked for and removed duplicate rows using drop_duplicates().
- Handled missing values using dropna() to ensure data integrity.
- Formatted date columns correctly for accurate chronological time-series analysis.

## 4. KPI Summary
|Metric |Value
| :--- | :--- |
 Total Revenue      $62,500.00 
 Total Orders       6 
 Average Order Value (AOV)     $10,416.67 

## 5. Trend Analysis
- Sales revenue over time was visualized using a time-series line chart.
- Observation: Revenue shows peak consistency across active order dates with periodic transaction surges rather than a flat daily line.

## 6. Customer Insights
- Top Categories:High-ticket items like Electronics and Apparel account for the highest proportion of customer spending.
- Payment Preferences:Digital payment modes (UPI/Cards) are preferred by customers over cash methods.

## 7. Visualization Section
Below is the integrated dashboard containing the key charts, graphs, and the final dashboard mockup:
![Dashboard Mockup](dashboard-mockup.png)

## 8. Key Findings
1. Electronics and Apparel are the primary revenue drivers for the business.
2. High average order values (AOV) indicate strong customer spending per transaction.
3. Transaction activity concentrates heavily on specific high-volume dates.

## 9. Recommendations
1. Prioritize stock management and marketing campaigns around high-demand product categories.
2. Optimize digital checkout flows to encourage higher customer retention.
3. Align promotional offers with the observed high-volume order dates.

## 10. Limitations or Assumptions
- Cleaning the dataset with dropna() removed incomplete entries, which slightly altered the aggregate metrics between the raw table and the final clean dashboard.
- Analysis is based on the initial Week 1 sample dataset provided.
