# 🛒 Console-Based Product Management System in C++

This is a simple **C++ console application** for managing products in an inventory system. It allows users to add, update, delete, and view products using a menu-based interface. This project is ideal for learning basic object-oriented programming and array handling in C++.

---

## 📋 Features

- Add new products
- Update existing product details
- Delete products by ID
- View all available products
- Search for a product by ID

---

## 🧱 Structure

### 1. `Product` Class
Represents a single product with:
- `id`: Unique identifier
- `name`: Product name
- `price`: Product price
- `description`: Product details
- `stock`: Inventory count

### 2. `ProductManager` Class
Handles operations for an array of up to 100 products:
- `addProduct()`
- `updateProduct()`
- `deleteProduct()`
- `viewProducts()`
- `getProductById(int id)`

---

## 🚀 Getting Started

### 🔧 Requirements
- A C++ compiler (G++, Clang, MSVC, etc.)
- C++11 or later
- Any C++ IDE or terminal

### 🛠 Compilation
To compile the program:

```bash
g++ -o product_manager main.cpp
