# 📦 Inventory Management System (Python + SQLite)

## 📌 Overview
This is a CLI-based Inventory Management System developed in Python using SQLite database.  
It helps manage products, track stock levels, record sales, and generate business reports in real-time.

The system simulates real-world retail/warehouse inventory operations.

---

## 🚀 Features

### 🛒 Product Management
- Add new products
- Update stock quantities
- Delete products
- Case-insensitive product search

### 📦 Stock Operations
- Increase stock
- Reduce stock after sales
- Automatic inventory updates

### 💰 Sales Tracking
- Record sales transactions
- Store sales history in database
- Auto-update stock after sale

### 📊 Reporting System
- Total inventory value
- Sales summary report
- Best-selling products
- Low stock alerts

---

## 🛠️ Technologies Used
- Python 3
- SQLite3 Database
- CLI (Command Line Interface)

---

## 📁 Project Structure


inventory_system/
│
├── main.py # Main menu (CLI interface)
├── db.py # Database operations (CRUD)
├── reports.py # Reporting module
└── inventory.db # SQLite database (auto-generated)


---

## ▶️ How to Run

### 1. Clone the repository
```bash
git clone https://github.com/your-username/inventory-system.git
2. Move into project folder
cd inventory-system
3. Run the application
python main.py
🧪 Sample Menu
===== INVENTORY MANAGEMENT SYSTEM =====
1. Add Product
2. Update Stock
3. Sell Product
4. View Inventory
5. Generate Reports
6. Delete Product
7. Exit
📊 Sample Reports
Total Inventory Value
Total Sales
Low Stock Items
Best Selling Products
⚙️ Future Improvements
GUI using Tkinter
Graphs using Matplotlib
Barcode scanning system
Supplier management module
Web-based version (Django/Flask)
👨‍💻 Author

Developed as a Python practice/project for learning database management and real-world system simulation.

📄 License

This project is open-source and free to use for educational purposes.
