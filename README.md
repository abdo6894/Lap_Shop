# 💻 LapShop - Laptop E-Commerce Website

LapShop is a full-stack web application built with **ASP.NET Core MVC**, designed for managing and selling laptops online. The system includes everything needed for both customers and administrators to interact with products, place orders, and manage inventory.

---

## 🚀 Features

### 👤 Users
- Browse laptops with full details.
- View multiple images per product.
- Add products to the shopping cart.
- Secure user registration and login.
- Place orders and view order history.

### 🛒 Products
- Display product name, description, price, category, and rating.
- Support for **multiple images per item**.
- Organized by categories (e.g., Dell, HP, Lenovo...).

### 🧑‍💼 Admin Dashboard
- Add / Edit / Delete products.
- Upload and manage product images.
- Manage categories and laptop brands.
- View and manage user orders.

---

## 🏗️ Project Architecture

This project follows a layered architecture:

- `LapShop` (Presentation Layer) - ASP.NET Core MVC Web App (views, controllers)
- `LapShop.BL` (Business Logic Layer) - Services, managers, validation logic
- `LapShop.Domain` - Entities (Product, Category, Order, etc.)
- `LapShop.DAL` - Database context and EF Core configurations

---

## 🛠️ Technologies Used

| Tech            | Description                                 |
|-----------------|---------------------------------------------|
| ASP.NET Core MVC| Web framework                               |
| Entity Framework Core | ORM for DB operations               |
| SQL Server      | Relational database                         |
| Bootstrap 5     | UI Framework for responsive design          |
| HTML/CSS/JS     | Frontend                                    |
| Git / GitHub    | Version control                             |
| Identity        | Authentication & Authorization              |

---

## 📦 Database Structure (Simplified)

- `Users` - App users (admins & customers)
- `Items` - Laptop products
- `ItemImages` - Images per product
- `Categories` - Product categories (HP, Dell, etc.)
- `Orders` - Orders made by users
- `OrderDetails` - Items per order
- `Cart` - Temporary shopping cart

---

## 🧪 How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/LapShop.git
