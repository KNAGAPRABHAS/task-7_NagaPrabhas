
---

```markdown
# 🛒 Task 7: Basic Sales Summary from SQLite using Python

## 📌 Objective

The goal of this task is to:
- Learn how to write and run basic SQL queries within Python.
- Practice importing SQL data into Python using `sqlite3` and `pandas`.
- Perform simple sales data summaries like total quantity and revenue.
- Visualize the data using a simple bar chart with `matplotlib`.

---

## 🛠 Tools Used

- Python 3.x
- SQLite (via `sqlite3` - built into Python)
- pandas
- matplotlib

---

## 🗃 Dataset

A small SQLite database file (`sales_data.db`) containing a single table:

**Table: `sales`**
| Column   | Type    | Description         |
|----------|---------|---------------------|
| id       | INTEGER | Auto-increment key  |
| product  | TEXT    | Product name        |
| quantity | INTEGER | Units sold          |
| price    | REAL    | Price per unit      |

---

## 🚀 How to Run

1. **Ensure required libraries are installed:**
   ```bash
   pip install pandas matplotlib
   ```

2. **Run the Python script:**
   You can run it in a `.py` file or Jupyter Notebook.

3. **What happens:**
   - Connects to the `sales_data.db` file.
   - Runs SQL queries to get:
     - Total quantity and revenue per product
     - Overall total quantity sold
   - Displays the result using `print()`.
   - Plots a bar chart for revenue per product.

---

## 📊 Output

### Printed Output:
- A summary table showing total quantity and revenue for each product.
- Total quantity sold across all products.

### Bar Chart:
- A bar graph showing revenue by product, saved as `sales_chart.png`.
  ![Screenshot (411)](https://github.com/user-attachments/assets/da3244a2-27c4-4d28-89c6-8e9812631ab5)


---

## 📂 Files Included

- `sales_data.db` – The SQLite database file.
- `sales_summary.py` or `.ipynb` – Python script to generate summaries and plot.
- `sales_chart.png` – Saved bar chart image.
- `README.md` – This file.

---

## ✅ Example Output

```
📦 Sales Summary by Product:

  product  total_qty  revenue
0   Apple         15     7.50
1  Banana         35    10.50
2  Orange         18    10.80


## 📎 Notes

- You can add more rows to the `sales` table to test with different data.
- Make sure to run the insert block only once to avoid duplicate entries.
- Modify the SQL queries for more advanced analytics as needed.

---

## 🔚 Conclusion

This task helps you understand how SQL and Python can be used together for simple yet powerful data analysis and visualization.

```

---
