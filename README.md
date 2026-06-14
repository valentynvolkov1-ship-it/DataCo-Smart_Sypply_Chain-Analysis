# DataCo Smart Supply Chain: Logistical & Financial Performance Analysis 

 
## 📌 Project Overview 

This project focuses on end-to-end data analysis of the **DataCo Smart Supply Chain** dataset from Kaggle. The goal was to clean and aggregate big data to evaluate logistics efficiency, delivery delays, and financial performance. 

 
## 🛠️ Tech Stack & Tools 

* **SQL (Google BigQuery):** Data aggregation, metric extraction (OTDR, Late Delivery Rate, Direct Losses). 

* **Tableau Public:** Data visualization and KPI dashboard construction. 

 
## 📊 Business Insights & Key Metrics 

Based on the analysis, the following key metrics were uncovered: 

* **Total Sales:** 36.78M ₽ | **Total Profit:** 3,97M ₽ 

* **On-Time Delivery Rate (OTDR):** **99.11%** — Indicates exceptional logistics reliability. 

* **Average Days Variance:** **-2.80 days** — Invoices are arriving faster than scheduled, suggesting that the company overestimates planned shipping timelines. 

* **Top Delayed Regions:** Southeast Asia, Eastern Asia, and Western Europe exhibit the highest count of late delivery statuses. 

 
## 📈 Dashboard Preview 

![Tableau Dashboard](https://github.com/valentynvolkov1-ship-it/DataCo-Smart_Sypply_Chain-Analysis/blob/67b07e065a03580551b0c1ad6c454565b1c150ed/Dashboard%201.png) 

 
🔗 **[View Interactive Tableau Dashboard Here](https://public.tableau.com/views/GlobalLogisticDeliveryPerfomanceDashboard/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)** 

 
## 💻 SQL Queries Used 

The data was aggregated in Google BigQuery using a comprehensive script. You can find the full script in the `delivery_perfomance_metrics.sql` (https://github.com/valentynvolkov1-ship-it/DataCo-Smart_Sypply_Chain-Analysis/blob/67b07e065a03580551b0c1ad6c454565b1c150ed/delivery_perfomance_metrics.sql.txt) directory. 


### Key Metrics Formulated: 

1. **Average Days Variance:** Calculates the gap between actual and scheduled shipping times. 

2. **Late Delivery Rate %:** Monitors the percentage of orders marked as 'Late delivery'. 

3. **Total Direct Losses:** Identifies transactions where `Order Profit Per Order < 0` to pinpoint profit leakage. 

 

## 🚀 How to Run 

1. The SQL script can be executed in any BigQuery environment holding the DataCo dataset. 

2. The interactive dashboard is hosted on Tableau Public and can be filtered by Region, Category, and Shipping Mode.


## Key business takeaway:
DataCo's logistics system operates reliably and quickly (high OTDR, ahead-of-schedule delivery), but suffers from operational inefficiencies in the supply chain in certain regions (Asia/Europe) and unprofitable sales that eat into margins. Optimizing planned delivery times and reducing direct losses (total_losses) are the company's primary growth areas.
