# 🛒 E-Commerce Platform

A simple PHP-MySQL based e-commerce website with **User** and **Admin** sections.

## Features

### 👤 User
- Register/Login/Logout
- View products with details
- Add items to cart & manage cart

### 🔑 Admin
- Secure login/logout
- Dashboard to manage products
- Add, edit, delete products

### 🗄️ Database
- `users` → stores customers & admins (with role field)
- `products` → product details (name, price, description, image)
- `cart` → tracks user cart items

### 🔒 Security
- Passwords hashed with `password_hash()`
- Sessions for login management
- Role-based access control for admins

## 🚀 Setup
1. Import the SQL file into MySQL.
2. Update `db.php` with your DB credentials.
3. Run the project in **XAMPP/WAMP** (htdocs folder).
4. Access via `http://localhost/project-folder`.

---

✅ This is a basic e-commerce project for learning PHP & MySQL.  
Future enhancements: order checkout, payment gateway, product search.
