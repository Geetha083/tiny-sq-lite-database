# 🛍️ Task 7: Basic Sales Summary Using Python and SQLite

## 🎯 Objective
Use SQL inside Python to pull sales data (total quantity, revenue) and visualize it with a bar chart.

## 🧰 Tools
- Python (with `sqlite3`, `pandas`, `matplotlib`)
- SQLite (no setup required — built into Python)
- Jupyter Notebook or .py script

## 📂 Folder Structure
```
Sales_Summary_SQLite_Python/
├── database/
│   └── sales_data.db               # Sample SQLite database
├── scripts/
│   └── sales_summary.py           # Python script
├── results/
│   └── sales_chart.png            # Output chart
├── README.md                      # This guide
```

## 📄 Dataset Info
Table: `sales`

Columns:
- `product` (TEXT)
- `quantity` (INTEGER)
- `price` (REAL)

## ✅ Steps Done in Code
1. Connect to `sales_data.db`
2. Run SQL query to get:
   - Total quantity sold per product
   - Total revenue per product
3. Display results using `print()`
4. Plot simple bar chart using `matplotlib`

## ▶️ Run This
You can run the script using:
```bash
python scripts/sales_summary.py
```

## 📈 Output
- Console print of sales summary
- Bar chart of revenue saved to `results/sales_chart.png`
