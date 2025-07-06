# 🛒 Instacart Purchase Pattern Analysis

**EDA (Exploratory Data Analysis)** project using real-world grocery delivery data from Instacart.  
Uncovers order trends, product demand, user behavior, and customer retention indicators.

---

## 📌 Project Overview

This project focuses on analyzing grocery ordering behavior on Instacart.  
It covers customer order frequency, preferred products, reorder behavior, peak ordering times, and more.  
Valuable insights are extracted to understand **when**, **what**, and **how** customers shop.

---

## 🔍 Key Insights

✅ Most orders are placed between **10 a.m. and 3 p.m.**  
✅ **Sunday and Monday** are the most active shopping days  
✅ Customers show strong loyalty to **organic** fruits and vegetables  
✅ Orders typically contain **1–15 items**  
✅ High reordering rates suggest weekly/monthly restocking habits  
✅ **Bananas** and **Organic Spinach** are top products  
✅ Reorder rates help identify repeat buyer trends  
✅ Opportunity: **Subscription model** or **recommendation engine** for recurring items

---

## 🧱 Dataset Structure

- **instacart_orders.csv** – Order details: date, user, order time
- **products.csv** – Product info: name, department, aisle
- **order_products.csv** – Items in each order (add-to-cart position, reordered flag)
- **departments.csv** – Department names
- **aisles.csv** – Aisle names

📦 Size:  
- 4.5+ million order-product records  
- 49K+ products  
- 478K+ orders

---

## 📂 Project Structure

📁 instacart-purchase-pattern-analysis
├── instacart_eda_analysis.ipynb
├── datasets/
│ ├── instacart_orders.csv
│ ├── products.csv
│ ├── order_products.csv
│ ├── aisles.csv
│ └── departments.csv
└── README.md


---

## 📈 Analysis Includes

- Order frequency by **hour** and **day of week**
- Customer wait time between orders
- Distribution of items per order
- Most **popular** and most **reordered** products
- Top products added first to cart
- Reorder **rate per product**
- Customer lifetime purchase patterns

---

## 🚀 Tools Used

- `pandas`, `numpy` for data manipulation  
- `matplotlib`, `seaborn` for visualization  
- `Jupyter Notebook` for analysis and presentation  

---

## 💡 Business Applications

- 📊 **Demand Forecasting**  
- 🧠 **Recommendation Systems**  
- 🔁 **Customer Retention Models**  
- 🛍️ **Personalized Promotions**  
- 📦 **Inventory Planning**  

---

## 📧 Contact

Created by [Edgar Jesús Martínez Chávez](https://www.linkedin.com/in/edaga/)  
📩 Email: econejes@gmail.com  
🔗 Portfolio: [GitHub.com/JesusMce](https://github.com/JesusMce)

---

⭐ If you like this project, give it a star!
