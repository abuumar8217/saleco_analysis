# 📊 SaleCo Database Analysis with SQLite & Python

This project analyzes `SaleCo.db` database using SQL queries executed within a Python environment (Google Colab or Jupyter Notebook). The database includes information about customers, invoices, vendors, products, and line-level transactions —  sales and inventory system.

---

## 🔍 What This Project Does

- Connects to a local SQLite database using Python (`sqlite3`).
- Explores and visualizes table structures using `pandas`.
- Answers practical business questions using SQL:
  - Count of invoices issued
  - Customers with balances over a threshold
  - Detailed itemized customer purchase history
  - Purchase subtotals by line items
  - Inventory valuation by product
  - Customers who made or didn’t make purchases during the invoice cycle

---

## 🛠️ Technologies Used

- Python 3.x
- SQLite3
- Pandas
- Google Colab / Jupyter Notebook

---

## 🚀 Getting Started

To run the notebook:

1. Clone this repository or open the notebook in Google Colab.
2. Make sure the `SaleCo.db` file is in the same directory as the notebook.
3. Run the cells in order.
4. Use `conn.close()` at the end to safely close the database connection.

---

## 🎯 Learning Goals

- Practice intermediate to advanced SQL queries.
- Use SQL JOINs and aggregate functions effectively.
- Understand customer and product relationships in a business context.
- Analyze inventory, financial balances, and customer activity.

---

## 📂 Files

- `SaleCo_Analysis.ipynb` - Main Colab notebook for analysis.
- `SaleCo.db` - SQLite database file containing all tables.
