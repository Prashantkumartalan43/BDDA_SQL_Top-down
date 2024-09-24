# MORE Retail SQL Database using Top-down approach


### Dataset Structure
The dataset is organized into multiple tables representing different entities such as customers, orders, products, payments, and more.

1. Customers Table

2. Managers Table

3. Orders Table

4. Payments Table

5. Products Table

6. Shelves Table


### Database Relationships
The database contains several tables that interact with each other based on key relationships. These relationships help in maintaining data integrity and enabling complex queries for in-depth analysis. Here's how the relationships between tables are structured:

-Customers → Orders (One-to-Many): A customer can place multiple orders, but each order is associated with only one customer.
   
-Orders → Payments (One-to-One): Each order has a single payment associated with it.
   
-Products → Orders (One-to-Many): A product can be ordered in multiple orders, but each line in the Orders table relates to one product.
   
-Managers → Shelves (One-to-Many): Each shelf is managed by one manager, but a manager can be responsible for multiple shelves.

-Products → Shelves (One-to-One): Each shelf holds only one product.
