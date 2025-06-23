# ecommerce-schema
# E-Commerce Database Schema

This project contains the SQL schema and ER diagram for an **E-Commerce Management System**, built as part of Task 1 for the SQL Developer Internship.

---

## Files Included

- `ecommerce_schema.sql` – SQL script that creates the full database schema.
- `ecommerce_er_diagram.png` – Entity Relationship Diagram exported from MySQL Workbench.
- `README.md` – Project explanation and table relationships.

---

##  Database Tables & Description

### 1. **Customers**
Stores user details like name, email, phone number, and address.

### 2. **Categories**
Groups products into logical sections (e.g., Electronics, Clothing, etc.)

### 3. **Products**
Details of items for sale. Linked to categories.

### 4. **Orders**
Stores details of customer purchases including total amount and date.

### 5. **OrderItems**
Line items of each order: which product, quantity, price, etc.

---

## Table Relationships

- Each **Customer** can place multiple **Orders**.
- Each **Order** can have multiple **OrderItems**.
- Each **OrderItem** is linked to one **Product**.
- Each **Product** belongs to one **Category**.

### ER Diagram View:

![E-Commerce ER Diagram]("e_commerce_ER.png")

---

##  Tools Used

- **MySQL Workbench** – For writing SQL and designing the ER diagram
- **MySQL CLI** – For executing SQL scripts in terminal
- **GitHub** – For version control and submission

---


