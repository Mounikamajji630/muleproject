# Customer-Order API (RAML 1.0)

This project demonstrates a **Customer and Order Management API** designed using **RAML 1.0**.  
It includes endpoints to manage customers, create orders, retrieve orders by ID, and uses reusable data types for clean design.  

---

## Base URI

# API Overview

### Customers

| Method | Endpoint | Description |
|--------|----------|------------|
| GET    | /customers | Retrieve all customers |
| POST   | /customers | Create a new customer |
| GET    | /customers/{customerId} | Retrieve customer details by ID |

### Orders

| Method | Endpoint | Description |
|--------|----------|------------|
| GET    | /orders | Retrieve all orders |
| POST   | /orders | Create a new order |
| GET    | /orders/{orderId} | Retrieve order details by ID |
