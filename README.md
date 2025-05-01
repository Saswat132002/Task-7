# Task-7
# 📊 Sales Summary using SQLite and Python

Hi! This is a simple project I worked on to practice working with SQLite databases using Python. The goal was to run basic SQL queries, get a sales summary, and visualize the results using a bar chart.

---

## 📁 What This Project Does

- Creates a SQLite database with a sample `sales` table
- Runs an SQL query to calculate:
  - Total quantity sold per product
  - Total revenue per product
- Displays the results using `pandas`
- Plots a simple revenue bar chart using `matplotlib`

---

## 🔧 Tools & Libraries Used

- Python 3
- SQLite (`sqlite3` module)
- Pandas
- Matplotlib

---

## 📊 Output Example

**Sales Summary:**

```
  product  total_qty  revenue
0   Apple         15     37.5
1  Banana         25     25.0
2  Orange         20     30.0
```

**Bar Chart:**

A bar chart showing total revenue for each product is saved as `sales_chart.png`.

---

## 🚀 How to Run It

1. Make sure you have Python installed.
2. Install required packages:

```bash
pip install pandas matplotlib
```

3. Run the notebook `Task7.ipynb` in Jupyter Notebook or VS Code.
4. The script will:
   - Create the database and insert data
   - Query and print results
   - Generate a bar chart

---

## 🎯 What I Learned

- How to write and execute SQL queries inside Python
- How to use `sqlite3` to interact with a database
- How to load SQL results into Pandas for analysis
- How to create simple visualizations with `matplotlib`

---

## ✅ Status

Project is complete and working as expected ✅

Thanks for checking it out!
```
