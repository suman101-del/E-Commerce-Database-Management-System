# E-Commerce-Database-Management-System
This project demonstrates the creation and management of a robust E-Commerce Database Management System. 
The schema is designed to handle core functionalities essential for e-commerce platforms, including user management, product listings, orders, cart operations, and customer reviews.
#User Management:
Tracks user details, including first name, last name, email, password hash, phone number, and address.
Includes unique email enforcement and timestamped record creation.
Product Listings:

Supports dynamic addition of products with attributes such as name, description, price, stock, and category.
Category mapping ensures product classification using a foreign key relationship.
Order Processing:

Handles order creation with user association, order status, and total amounts.
Maintains detailed records of individual products within each order, including quantity and pricing.
Customer Reviews:

Facilitates product reviews with user ratings (1 to 5) and optional comments.
Shopping Cart:

Allows users to add products to a personal shopping cart with adjustable quantities.
Relational Database Design:

Follows best practices for normalization and referential integrity using foreign key constraints.
Technologies Used:
Database: MySQL
Key Components: Users, Products, Orders, OrderDetails, Reviews, Cart, and Categories tables.
Sample Data:
Populated with realistic sample data to simulate operations such as order placement, product reviews, and cart updates.
Applications:
This database can be integrated into any e-commerce platform to provide a solid backend for inventory management, user activity tracking, and transactional operations.

