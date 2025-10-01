# Retail-Sales-Analytics

This project uses a sample dataset from Kaggle to demonstrate end-to-end retail sales analysis using **BigQuery** on **Google Cloud** for data querying and **Power BI** for visualization and reporting.  

It includes:
- Data modeling  
- DAX measures  
- Interactive dashboards  
- Sales performance analysis  
- Product insights  
- Customer trends  

## Tech Stack
- **BigQuery** (Google Cloud) – SQL queries for data extraction & transformation  
- **Power BI** – dashboards, visuals, KPIs  
- **Kaggle Dataset** – retail sales data  

## What I Did
1. Download the sample retail dataset from [Kaggle](https://www.kaggle.com/datasets/logiccraftbyhimanshi/walmart-customer-purchase-behavior-dataset/data).  
2. Upload the dataset to BigQuery on Google Cloud.  
3. Use SQL queries in BigQuery to transform and aggregate the data into tables that will be used in Power BI. Key steps included:

   - Cleaning the raw dataset (removing duplicates, formatting dates)  
   - Creating aggregated tables for sales, customers, and products  
   - Segmenting data by demographics (e.g., age group) and geography (e.g., city, region)  
   - Calculating key metrics such as total sales, total revenue, and average transaction value  

   Examples of the SQL queries used to create these tables and generate key metrics can be found in the attached file:  
   [BigQuery SQL Examples](https://github.com/user-attachments/files/22645721/BigQuery_SQL.pdf)

   These tables were then ready to be connected directly in Power BI for visualization.

4. Open Power BI and connect to the tables created in BigQuery.  
   - Import fact and dimension tables into Power BI  
   - Establish relationships between tables (**many-to-one** from dimension tables to fact table)  
   - Create DAX measures for KPIs such as Total Sales, Average Transaction Value, and Total Customers  
   - Build dashboards and interactive visualizations using the prepared tables  

   For reference on layout, structure, and recommended dashboard design, see the attached Power BI file:  
   [Power BI Report & Model View](https://github.com/user-attachments/files/22644778/PowerBIReportandModelView.pdf)

## Author
Randy Grullon
