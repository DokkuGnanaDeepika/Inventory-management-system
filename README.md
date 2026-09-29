# Mini-project-on-Inventory-Management-System
A console-based Python application for managing inventory stocks, allowing users to select products, add stock, record sales, and monitor current quantities.
# Inventory Management System

A beginner-friendly, interactive command-line application built in Python to manage product inventory levels efficiently.

## 📌 Features

- **Initial Stock Setup:** Initialize starting stock quantities for products.
- **Product Selection:** Select specific inventory items (e.g., Rice, Sugar, Oil).
- **Stock Operations:**
  - **Add Stock:** Increase inventory quantities when new stock arrives.
  - **Sell Stock:** Deduct stock upon sale with built-in stock availability checks to prevent overselling.
  - **Check Stock:** Instantly view remaining stock levels for specific items.
- **Interactive Menu:** Simple CLI loop allowing multiple stock transactions in a single session.

### 🛠️ Core Concepts Demonstrated

- **Input/Output Handling:** Reading user input using `input()` and casting strings to integers using `int()`.
- **Control Flow:** Using `if-elif-else` statements for nested decision-making.
- **Iteration:** Using a `for` loop and the `break` keyword to control program execution flow.
- **Basic Data Validation:** Checking stock levels before performing a sale to prevent invalid inventory states.
