# Inconvenient Convenience Store

A convenience store is a small retail business that stocks everyday items for regular use, providing a financial boost to the economy and economic stability. These stores offer quick solutions for smaller shopping needs, delivering speedy service to time-starved customers. In the US, there is approximately one convenience store for every 2,100 people, indicating the significant market size and future growth potential of the convenience store industry.

At Pluto Convenience Store, transactions are recorded manually, often leading to missed entries and errors. Manual recording increases the risk of mistakes and miscalculations, and records can easily be lost due to the busy nature of the staff. Additionally, the inventory lacks a specific record-keeping system for product data. Effective transaction tracking is essential but currently missing in the store. A computerized system would simplify management activities for the owner, reduce paperwork, and ease the workload for both the owner and staff.

Our project aims to provide an accessible way to track transactions, sales, and inventory. It enables users to create, update, and store information about products and transactions. This system is designed for store owners who currently use manual transaction methods and struggle to maintain supply and demand balance. By reducing errors and saving time, the system will increase the store's efficiency and sales, ultimately improving the experience for both employees and customers.

We aim to design a system that enhances profits and sales while offering a better experience for employees and customers. The database will store information about employees, customers, orders, inventory management, product categories, billing processes, product quantities, and suppliers.

## Requirements

1. **Admin-Employee Relationship**
   - An admin can grant access to an unlimited number of employees.
   - Each employee can have only one admin.

2. **Order Preparation**
   - Employees can prepare an unlimited number of orders.
   - Each order (billing) can be handled by only one employee.

3. **Order-Product Relationship**
   - One order can include at least one to an unlimited number of products.
   - At least one product is required to place an order.

4. **Supplier-Product Relationship**
   - A supplier can supply multiple but at least one product.
   - One or multiple products can be supplied by a single supplier.

5. **Order-Bill Relationship**
   - An order can generate only one bill.
   - One bill is associated with only one order.

6. **Inventory-Order Relationship**
   - An inventory can prepare an unlimited number of orders.
   - Each order originates from only one inventory.

7. **Inventory-Category Relationship**
   - One inventory can contain an unlimited number of categories.
   - All categories are stored within one inventory.

8. **Customer-Order Relationship**
   - A customer can place an unlimited number of orders.
   - Each order can be placed by only one customer.
