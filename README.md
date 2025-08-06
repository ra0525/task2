<h1 align="center"> Data Visualization and Storytelling </h1>

## **📈 Objective**
The goal of this project is to analyze and derive actionable insights from a retail dataset (Superstore) using Tableau. The focus is on visualizing sales, profit, customer segments, and regional performance to support business decision-making and uncover hidden patterns.

---

## **📁 Dataset Details**
- **Name:** Superstore
  - Contains records of customer orders including order ID, date, customer name, region, category, sub-category, sales, profit, discount, and shipping details.
- **Source:** Kaggle [Link](https://www.kaggle.com/datasets/arpitagupta11/superstore-csv)
- **File:** `Superstore.csv`
- **Rows:** ~10,000 rows

---

## **🛠️ Tools Used**
- **Tableau** for Data Visualization & Storytelling
- Calculated Fields, Filters, and Parameters used in Tableau

---

## **📈 Sheets Overview (Visualizations Created):**
**1. Sales and Profit Over Time**

**Details:**
- **Chart Type:** Line chart
- **X-Axis:** Order Date (Year).
- **Y-Axis:** Sales and Profit.
- **Insight:** Helps understand how sales and profit trend over time (seasonality, spikes, drops).

**2. Sales by Category & Sub-Category**

**Details:**
- **Chart Type:** Horizontal/vertical bar chart
- **X-Axis:** Sales
- **Y-Axis:** Category and Sub-Category.
- **Insight:** Identifies top-selling categories and sub-categories; highlights where most revenue comes from.

**3. Profit by Region**

**Details:**
- **Chart Type:** Map chart
- **Dimension:** Region.
- **Measure:** Profit.
- **Insight:** Shows which regions are profitable and which are underperforming.

**4. Sales vs Profit**

**Details:**
- **Chart Type:** Scatter plot
- **X-Axis:** Sales.
- **Y-Axis:** Profit.
- **Insight:** Correlation between sales and profit. Products or categories with high sales but low profit can be identified.

**5. Orders by Ship Mode**

**Details:**
- **Chart Type:** Pie chart or bar chart.
- **X-Axis:** Count of Order ID
- **Y-Axis:** Ship Mode
- **Insight:** Which shipping methods are most preferred and their contribution to total orders.

---

## **📊 Final Dashboard: "Sales Performance Dashboard"**
- **Contains:**
  - Sales vs Profit Overview
  - Regional Performance
  - Category/Sub-Category Wise Contribution
  - Customer Sales Leaderboard
  - Monthly Sales Trend

- **Interactivity:**
  - Region filter
  - Dynamic sub-category drill-down
  - Hover tooltips for profit/sales insights

- **Design:**
  - Clean layout
  - Color-coded profit/loss
  - Fully responsive with interactive filters

---

## **🧠 Insights & Business Recommendations:**

| Insight | Recommendation |
| ----- | ----- |
| 📉 Tables show high sales but negative profit | Revisit pricing or reduce discounts |
| 📍 West & East outperform South | Focus marketing & logistics on Southern region |
| 📅 Nov–Dec peak sales months | Boost stock & ads during festive season |
| 👤 Top 10 customers bring major sales | Launch loyalty programs or personalized offers |
| 💡 Technology is the most profitable | Invest more in tech inventory and promotions |

---

## **📝 Conclusion:**
The Tableau dashboard provides a comprehensive overview of sales performance, enabling stakeholders to understand patterns, identify profitable categories and customers, and make informed decisions. With its interactivity and visual clarity, the dashboard can be a strong asset for strategic planning.
