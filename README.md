# 🏪 Grocery Market Management System

A complete **Python-based Grocery Market Management System** built using Jupyter Notebook. This system helps manage inventory, billing, customers, and generate reports for a grocery store.

---

## 📌 Features

### 📦 Inventory Management
- Add new products
- View all products in a formatted table
- Update product price and stock
- Delete products

### 🧾 Billing System
- Add items to cart
- Auto stock deduction after billing
- GST (5%) calculation
- Generate formatted invoice/bill
- Save bills to `sales.csv`

### 👥 Customer Management
- Add new customers with auto-generated ID
- View all customers
- Search customer by name or phone
- Delete customer
- View customer purchase history

### 📊 Reports & Analytics
- Daily Sales Report
- Best Selling Products
- Low Stock Alert (Stock < 5)
- Overall Summary Report

---

## 🗂️ Project Structure

```
grocery-market-system/
│
├── Grocery_System.ipynb     ← Main Jupyter Notebook
├── products.csv             ← Product data (auto-created)
├── sales.csv                ← Sales records (auto-created)
├── customers.csv            ← Customer data (auto-created)
└── README.md                ← Project documentation
```

---

## 🛠️ Technologies Used

| Technology | Purpose |
|-----------|---------|
| Python 3  | Core programming language |
| CSV Module | File-based data storage |
| OS Module | File management |
| Datetime Module | Auto bill number & date |
| Jupyter Notebook | Development environment |

---

## 📋 System Cells Overview

| Cell | Module | Description |
|------|--------|-------------|
| Cell 1 | Setup | Import libraries & initialize CSV files |
| Cell 2 | Inventory | Add, View, Update, Delete products |
| Cell 3 | Inventory Menu | Inventory navigation menu |
| Cell 4 | Billing | Cart, Invoice, GST, Stock update |
| Cell 5 | Billing Menu | Billing navigation menu |
| Cell 6 | Customer | Add, View, Search, Delete customers |
| Cell 7 | Customer Menu | Customer navigation menu |
| Cell 8 | Reports | Daily sales, Best sellers, Low stock |
| Cell 9 | Reports Menu | Reports navigation menu |
| Cell 10 | Main Menu | Connects all modules together |

---

## ▶️ How to Run

### Step 1 — Clone the Repository
```bash
git clone https://github.com/yourusername/grocery-market-system.git
cd grocery-market-system
```

### Step 2 — Open Jupyter Notebook
```bash
jupyter notebook Grocery_System.ipynb
```

### Step 3 — Run Cells in Order
Run each cell from **Cell 1 to Cell 10** in order.

### Step 4 — Start the System
After running all cells, the **Main Menu** will appear:
```
=============================================
   🏪 GROCERY MARKET MANAGEMENT SYSTEM   
=============================================
  1. 📦 Inventory Management
  2. 🧾 Billing System
  3. 👥 Customer Management
  4. 📊 Reports & Analytics
  5. 🚪 Exit
=============================================
```

---

## 📸 Sample Output

### 📦 Product List
```
ID     Name                 Category        Price    Stock
------------------------------------------------------------
1      Milk                 Dairy           ₹ 45.00      20
2      Chips                Snacks          ₹ 20.00      50
3      Rice                 Grains          ₹ 60.00      30
```

### 🧾 Sample Bill
```
==================================================
         🛒 GROCERY MARKET BILL             
==================================================
  Bill No  : BILL20240411123045
  Date     : 11-04-2024 12:30
  Customer : Tanuja
==================================================
Product               Qty    Price       Total
--------------------------------------------------
Milk                    2   ₹ 45.00   ₹   90.00
Chips                   3   ₹ 20.00   ₹   60.00
--------------------------------------------------
                          SUBTOTAL   ₹   150.00
                          GST (5%)   ₹     7.50
==================================================
                        GRAND TOTAL  ₹   157.50
==================================================
      Thank you for shopping! 😊           
==================================================
```

### 📊 Summary Report
```
==================================================
         📈 OVERALL SUMMARY REPORT            
==================================================
  👥 Total Customers    : 5
  📦 Total Products     : 10
  ⚠️  Low Stock Items    : 2
  🧾 Total Bills        : 8
  🛒 Total Items Sold   : 45
  💰 Total Revenue      : Rs.3500.00
  💸 GST (5%)           : Rs.175.00
  💵 Grand Total        : Rs.3675.00
==================================================
```

---

## 💡 Concepts Used

| Concept | Used In |
|---------|---------|
| Functions | All modules |
| CSV File Handling | All modules |
| While Loops & Menus | All menus |
| CRUD Operations | Inventory & Customer |
| List Comprehension | Search & Filter |
| Datetime Module | Bill No & Date |
| Sorting with Lambda | Best Sellers |
| set() for unique values | Reports |
| GST Calculation | Billing |
| Modular Programming | All cells |

---

## 🚀 Future Improvements

- [ ] Add SQLite database instead of CSV
- [ ] Add Streamlit web interface
- [ ] Add data visualizations (charts)
- [ ] Add export to PDF feature
- [ ] Add user login system

---

## 👩‍💻 Author

**Tanuja Nikam**
- 🎓 BScIT Student
- 💼 Aspiring Data Analyst
- 🌍 Maharashtra, India

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

⭐ **If you found this project helpful, please give it a star!** ⭐
