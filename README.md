Sales Performance Dashboard (2023–2025) — Power BI

An interactive Power BI dashboard analyzing 1,200+ orders across products, customers, payment methods, and time, built on a cleaned star-schema data model.

📌 Dashboard KPIs


💰 Total Revenue
🛒 Total Orders
👥 Total Customers
📦 Total Quantity Sold
💵 Average Order Value (AOV)


🚀 Features


Revenue trend over time with 3-month moving average
Product and category-level revenue breakdown
Payment method and coupon usage analysis
Referral source performance (Instagram, Email, Google, Facebook, Referral)
Order status distribution (Delivered, Shipped, Pending, Returned, Cancelled)
Monthly revenue heatmap by year
Dynamic slicers: Year, Product, Order Status, Payment Method, Referral Source, Coupon Code
Key insights & recommendations panel for quick decision-making


🗂️ Data Model

Star schema with one fact table and three dimension tables:


Fact_Orders — order-level transactions
Dim_Product — product-to-category mapping
Dim_Customer — unique customer list
Dim_Date — full calendar table for time intelligence


🛠️ Tools & Technologies


Microsoft Power BI
Power Query
DAX
Data Modeling
Microsoft Excel


📁 Files


Dataset_for_Data_Analytics_Cleaned.xlsx — cleaned source data (star schema)
Sales Performance Dashboard.pbix — Power BI report file
