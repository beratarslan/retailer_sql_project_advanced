# **E-Commerce Sales Analysis Project**

### **Difficulty Level: Advanced**

---

## **Project Overview**

In this project, I explored a dataset of over 20,000 sales records from an e-commerce platform, diving deep into customer behavior, product performance, and overall sales trends using PostgreSQL.

Throughout the analysis, I tackled key business challenges such as revenue tracking, customer segmentation, and inventory optimization. Additionally, I focused on data cleaning, managing missing values, and crafting structured queries to extract meaningful insights.

To provide a clearer understanding of the database structure, I’ve also included an ERD diagram that visually maps out the relationships between different tables.


### **Database Schema Overview**

The database is structured to capture key aspects of an e-commerce platform, including products, customers, orders, and payments. Below is a high-level breakdown of the schema:

- **Products & Categories**: Products are categorized to allow efficient filtering and analysis of different product types. Each product has attributes like price and cost of goods sold (COGS).  
- **Customers & Sellers**: The database keeps track of customer details (name, address, state) and seller information (origin, name).  
- **Orders & Order Items**: Orders are linked to both customers and sellers. Each order consists of multiple items, with details on quantity and price per unit.  
- **Payments & Shipping**: Payment records store transaction details, while the shipping table tracks delivery status, shipping providers, and return dates.  
- **Inventory Management**: The inventory system monitors product stock levels, warehouse locations, and restocking dates.  

To provide a clear visual representation of the relationships between these tables, refer to the **ERD diagram** below:



![E-Commerce ERD](images/e_commerce_erd_diagram.png)
