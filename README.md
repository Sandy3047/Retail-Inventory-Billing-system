# 🛒 Multi-Category Retail Inventory & Billing System

A simple, browser-based application designed for small to medium retail businesses. It offers features such as inventory management, interactive billing, category-wise filtering, and performance insights — all in a single lightweight system.

---

## 📌 Features

### ✅ Homepage
- Store name/logo with a welcome message.
- Quick links to: Billing, Inventory, Insights.
- Summary view: total stock items and product categories.

### 🗂️ Categories Module
- Add, edit, or delete product categories (e.g., Grocery, Electronics, Clothing).
- Filter billing and inventory views based on category.

### 🧾 Billing System
- Select category and then product.
- Input quantity — auto-calculate:
  - Subtotal
  - Tax (if applicable)
  - Discounts (optional)
  - Total payable
- Generate printable invoice.
- Auto-update stock after successful billing.

### 📦 Inventory Management
- Add/Edit/Delete product details:
  - Name, SKU/Code, Category, Price, Stock Quantity
- Search, filter, and view all products.
- Low stock alert system.

### 📊 Sales Insights & Reports
- Visual sales analysis using charts:
  - Sales by category/product/date
  - Best-selling and low-stock products
- View reports (daily/weekly/monthly)

---

## 🧪 Optional Enhancements
- Multi-user login system (Admin, Cashier, Inventory Manager)
- Data export (CSV/PDF)
- Expiry alerts for perishable stock
- Secure login with password protection

---

## 🛠️ Tech Stack

| Layer      | Technology                |
|------------|----------------------------|
| Frontend   | HTML, CSS, JavaScript (or React/Vue) |
| Backend    | Node.js or Python Flask     |
| Database   | Google Sheets or Excel     |
| Charts     | Chart.js / ApexCharts / Google Charts |

---

## 🚀 Getting Started

### Prerequisites
- Node.js / Python installed
- A code editor (VS Code recommended)
- Internet connection (for using Google Sheets or online chart libraries)

### Clone the Repo
```bash
git clone https://github.com/yourusername/retail-inventory-billing-system.git
cd retail-inventory-billing-system

npm install
npm start

/public
  └── index.html
/src
  ├── assets/
  ├── components/
  ├── pages/
  └── app.js
/backend
  └── server.js (Node/Flask)

The link for the website
https://resonant-pavlova-f75ddc.netlify.app/
