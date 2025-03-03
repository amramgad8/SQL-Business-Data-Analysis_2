# 🚀 SQL Business Data Analysis

## 📖 Overview  
This project focuses on **analyzing business data using SQL** to extract meaningful insights, optimize decision-making, and improve business performance. The analysis covers **database exploration, customer segmentation, product performance, sales trends, and revenue insights**.  

📌 **The project script (`SQL_Scripts.sql`) is included in this repository for reference and execution.**  

## 📂 Data Structure  
The dataset follows a **star schema** with the following tables:  

### 🔹 `gold.dim_customers` (Customer Dimension)  
- **Personal Information**: `first_name`, `last_name`, `birthdate`, `gender`  
- **Geographical Data**: `country`  
- **Additional Attributes**: `marital_status`, `create_date`  

### 🔹 `gold.dim_products` (Product Dimension)  
- **Identification**: `product_key`, `product_id`, `product_number`  
- **Categorization**: `category`, `subcategory`  
- **Financial Data**: `cost`, `maintenance_cost`  
- **Time-Based Data**: `start_date`  

### 🔹 `gold.fact_sales` (Fact Table)  
- **Order Details**: `order_number`, `order_date`, `shipping_date`, `due_date`  
- **Financial Metrics**: `sales_amount`, `quantity`, `price`  
- **Relationships**: Links to `dim_customers` via `customer_key` and `dim_products` via `product_key`  

## 🔍 Exploratory Data Analysis (EDA)  
### ✅ **Database Exploration**  
- Retrieve table structures and metadata.  
- Inspect column details for better understanding.  

### ✅ **Dimension Analysis**  
- Analyze customer demographics (age, gender, country).  
- Explore product categories and price variations.  

### ✅ **Time-Based Analysis**  
- Determine the first and last recorded orders.  
- Measure customer age distribution.  

### ✅ **Key Metrics**  
- Calculate total sales revenue.  
- Track the number of unique customers and total transactions.  
- Compute average selling price across products.  

### ✅ **Magnitude & Ranking Analysis**  
- Identify top-selling products and high-spending customers.  
- Rank best and worst-performing products based on revenue.  
- Analyze sales distribution across different countries and categories.  

## 📊 Key Insights & Findings  
📌 Some product categories generate **higher revenue**, while others have **low sales despite high costs**.  
📌 Certain regions have a **higher concentration of high-spending customers**, indicating a potential for targeted marketing.  
📌 Some customers **place frequent orders**, contributing significantly to overall sales.  
📌 Underperforming products require **strategic promotions or price adjustments** to improve sales.  

## 🚀 Recommendations  
✔ **Enhance Marketing Strategies** – Focus on promoting underperforming products through targeted campaigns, discounts, and improved visibility.  
✔ **Expand in High-Value Markets** – Identify and target regions with high-spending customers by tailoring offers and optimizing distribution channels.  
✔ **Optimize Pricing for Profitability** – Analyze pricing trends, adjust product prices based on demand and competition, and implement dynamic pricing strategies.  

## 🛠️ Technologies Used  
- **SQL** – Data extraction, transformation, and analysis.  
- **Microsoft SQL Server** – Database management and query execution.  
- **Jupyter Notebook** – Query execution and visualization.  

## 📎 How to Use This Repository  
1. Clone the repository:  
   ```sh
   git clone https://github.com/your-username/SQL-Business-Data-Analysis.git
   ```  
2. Open the `SQL_Scripts.sql` file and execute the queries in **Microsoft SQL Server**.  
3. Modify queries as needed for custom analysis.  

## 📢 Contributing  
Contributions are welcome! Feel free to submit a **pull request** or open an **issue** for suggestions and improvements.  

## 📜 License  
This project is licensed under the **MIT License**.  

## 📞 Contact  
📌 **Created by:** Amr Amgad Mashaly  
📧 **Email:** amrmashaly935@.com  
📱 **Phone:** 01009218738  

