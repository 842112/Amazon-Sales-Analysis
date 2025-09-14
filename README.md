# Amazon-Sales-Analysis
Performed data cleaning, exploratory analysis, and visualization on Amazon’s sales dataset to uncover insights on sales performance, customer behavior, fulfillment efficiency, product demand, and geographical distribution.
---

# 📊 Amazon Sales Analysis using Python

## 💡 Project Summary

Performed **data cleaning, exploratory analysis, and visualization** on Amazon’s sales dataset to uncover insights on **sales performance, customer behavior, fulfillment efficiency, product demand, and geographical distribution**. The project highlights trends, bottlenecks, and growth opportunities to **optimize sales strategies and improve customer satisfaction**.

---

## ❓ Problem Statement

Amazon handles millions of sales transactions across multiple categories, fulfillment methods, and regions. However, raw sales data often comes with challenges such as:

* Missing or inconsistent values
* High variation in customer behavior across geographies
* Lack of structured insights into sales performance, fulfillment, and product demand

The goal was to **analyze sales trends, customer segments, and geographical performance** to generate **actionable business insights**.

---

## 📂 Dataset

* **File:** `Cleaned_Amazon_Sale_Report.csv`
* **Key Fields:**

  * `Order ID`, `Date`, `Amount`, `Category`, `Size`, `Qty`, `Fulfilment`, `ship-state`, `ship-city`, `Status`

---

## 🛠 Tools & Technologies

* **Language:** Python
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
* **Environment:** Jupyter Notebook / VS Code

---

## ⚙️ Methodology

### 1️⃣ Data Preparation & Cleaning

* Handled missing values and duplicates
* Converted data types (e.g., dates, numerical fields)
* Removed invalid/irrelevant records

### 2️⃣ Exploratory Analysis

* **Sales Overview:** Monthly revenue trends, order distribution, AOV (Average Order Value)
* **Product Analysis:** Popular categories, product sizes, revenue by category
* **Fulfillment Analysis:** Delivery status by fulfillment method, order counts, AOV by fulfillment type
* **Customer Segmentation:** Orders and spending by top cities/states
* **Geographical Analysis:** State & city-level contribution to sales and orders

### 3️⃣ Visualization

* Bar charts for **top products, categories, and cities**
* Pie chart for **sales share across states**
* Line plots for **monthly sales trends**
* Scatter plots for **orders vs sales (city-wise)**

### 4️⃣ Business Insights

* Seasonal peaks in sales (promotional/holiday-driven demand)
* High concentration of orders in **metro states & cities**
* Returns & cancellations impacting customer experience
* Strong correlation between **order frequency and total spend**

---

## 🔍 Key Insights

✔ Maharashtra & Karnataka drive the highest revenue, led by metro cities like **Bengaluru, Mumbai, and Hyderabad**
✔ Bengaluru has **high order frequency**, while Hyderabad shows **higher AOV** → different customer behaviors
✔ Certain months show clear **sales peaks** (likely festivals/promotions)
✔ **Majority of orders are successful**, but cancellations/returns still impact customer trust
✔ Product demand is **uneven across categories**, with a few categories dominating sales

---

## 📊 Outputs

* Cleaned and structured sales dataset
* Visualizations:

  * Top states & cities by sales
  * Monthly revenue trends
  * Order status distribution
  * Product category breakdown
  * Scatterplot of orders vs revenue
* Business insights report (PDF/Markdown)

---

## ▶️ How to Run This Project

1. Clone the repository
2. Place dataset `Cleaned_Amazon_Sale_Report.csv` in the `/data` folder
3. Run the Jupyter Notebook `Amazon_Sales_Analysis.ipynb`
4. Outputs:

   * Plots & visualizations
   * Business insights summary

---

## 📈 Results & Conclusion

This project demonstrates how **Python-based data analysis** can transform raw sales data into **business intelligence**:
✅ Identified **seasonal sales patterns** for targeted campaigns
✅ Pinpointed **high-value states & cities** for marketing focus
✅ Highlighted **fulfillment challenges** impacting customer satisfaction
✅ Segmented customers by **spending & order behavior** to optimize loyalty programs

By leveraging these insights, Amazon (or any e-commerce platform) can **refine pricing strategies, optimize fulfillment, and build stronger customer engagement for long-term growth.**
