# -Customer-Segmentation-Analysis-using-SQL
# 🏆 Customer Segmentation Analysis  

## 📌 Project Overview  
Customer segmentation helps businesses understand their customer base by grouping them into different categories based on their spending behavior. This project analyzes customer transactions and classifies them into various segments to derive valuable insights.  
## 📊 Dataset Information  
The dataset used in this project contains customer and transaction details with the following key attributes:  

- **customer_id**: Unique identifier for each customer  
- **name**: Name of the customer  
- **location**: Country/region of the customer  
- **total_spent**: Total amount spent by the customer  
- **transaction_id**: Unique identifier for each transaction  
- **txn_date**: Date of the transaction  
- **amount**: Amount spent in a single transaction  

---

## 🚀 Project Steps  

### **1️⃣ Database Setup**  
- Selected PostgreSQL as the database to store customer and transaction data.  
- Created tables for customers and transactions with appropriate constraints.  

### **2️⃣ Data Import**  
- Inserted sample data into the PostgreSQL tables.  
- Verified data integrity using:  
  ```sql
  SELECT * FROM customers;
  SELECT * FROM transactions;
---

## 🚀 Steps in the Analysis  
1. **Data Preparation:**  
   - Created tables for customers and transactions.  
   - Inserted sample data.  

2. **Customer Segmentation:**  
   - Classified customers into **High Spender, Medium Spender, and Low Spender** based on their total spending.  

3. **Top Spending Customers:**  
   - Identified the top 5 highest-spending customers.  

4. **Monthly Spending Trends:**  
   - Analyzed spending patterns grouped by month.  

5. **Customer Behavior Analysis:**  
   - Determined total transactions, total spent, and average spent per customer.  
   - Identified returning customers (who made multiple purchases).  
   - Detected inactive customers (who haven't purchased in the last 3 months).  

6. **Revenue Insights:**  
   - Found customers spending above the average.  
   - Ranked locations based on total revenue generated.  

---

## 📈 Insights & Findings  
- **40% of customers are high spenders**, contributing significantly to total revenue.  
- Customers in **Singapore and India** generated the highest revenue.  
- **Returning customers** tend to spend more over time.  
- **30% of customers have not made any purchases in the last 3 months**, indicating possible churn.  

---

## 🛠 Tools Used  
## Setup Information  

- **Database:** PostgreSQL  
- **Query Execution:** pgAdmin / psql CLI  
 

---

## ⚙️ How to Run the Project  
## How to Set Up and Run the Project  

- Install PostgreSQL on your system.  
- Create a new database in PostgreSQL.  
- Run the SQL script (**Customer Segmentation.sql**) to create the table and load the data.  
- Execute the analysis queries to derive insights.

---

## 🔮 Future Improvements  
🚀 Perform advanced segmentation using clustering techniques like K-Means.  
📊 Visualize customer spending trends using Power BI or Tableau.  
🖥️ Build an interactive dashboard for real-time customer insights.  

---

## 🎯 Conclusion  
This project provides valuable insights into customer spending behavior and segmentation using SQL queries. It demonstrates how SQL can be used to analyze and classify customers efficiently, helping businesses optimize marketing strategies and improve customer retention.  

