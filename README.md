# UrbanCart-Sales-Analytics-SQL-Based-Business-Insights

![UrbanCart Sales Overview](https://raw.githubusercontent.com/NaimurRah1/UrbanCart-Sales-Analytics-SQL-Based-Business-Insights/main/image/page1.png)
In this project ,  I analyze UrbanCart’s sales data using SQL to uncover business insights related to customers, revenue, products, and purchasing behavior.
## About the Project
![UrbanCart Sales Overview](https://raw.githubusercontent.com/NaimurRah1/UrbanCart-Sales-Analytics-SQL-Based-Business-Insights/main/image/page2.png)

This project analyzes UrbanCart’s sales data using SQL to uncover actionable business insights related to revenue performance, product trends, and customer purchasing behavior. By querying transactional and dimensional data from tables such as fact_order, fact_order_items, dim_products, and dim_customers for the period from October 1, 2025, to September 30, 2025, the analysis explores key questions including revenue distribution, top-performing and underperforming products, frequently purchased product combinations, customer ordering patterns, and drivers of order value. The objective is to evaluate overall sales performance, identify top products and customers, recognize emerging trends, and support data-driven business decision-making through insights on revenue, order quantity, and transaction patterns
##  ER Diagram view
![UrbanCart Sales Overview](https://raw.githubusercontent.com/NaimurRah1/UrbanCart-Sales-Analytics-SQL-Based-Business-Insights/main/image/page3.png)

**Discussion:**  
The ER diagram illustrates the database structure of the system by showing the main entities and their relationships. It includes entities such as Customers, Orders, Order_Items, and Products, where each entity represents a table in the database. The relationships indicate how customers place orders and how each order consists of multiple products. Primary keys uniquely identify each record, while foreign keys are used to maintain relationships between tables, ensuring data integrity and reducing redundancy.

---

### 1. Order Distribution
![UrbanCart Sales Overview](https://raw.githubusercontent.com/NaimurRah1/UrbanCart-Sales-Analytics-SQL-Based-Business-Insights/main/image/page4.png)

**Discussion:**  
Order Summary (September 30, 2025 – October 1, 2025)
During this period, UrbanCart recorded a total of 1,200 orders. Among them, 713 orders were successfully completed. The remaining 487 orders were not completed, with 241 orders still in a pending state and the rest having been cancelled.

---

### 3. Product Pair Revenue
![Product Pair Revenue](images/img3.png)

**Discussion:**  
The combination of Miniket Rice 5Kg and Power Bank generates the highest revenue when purchased together.
