
# 📊 Amazon Sales Analysis Project

This project explores and analyzes Amazon sales data using Python (Pandas, Seaborn, Matplotlib) and Power BI for interactive dashboarding. It helps uncover sales trends, top-performing products, and actionable insights across different categories and brands.

## 🧾 Dataset Overview

- **Source**: Amazon Sales Data (Records: 5901)
- **Time Period**: Jan 2019 – Dec 2020
- **Columns**:
  
    - Order ID, Order Date, Ship Date, Ship Mode,
    - Customer ID, Customer Name, Segment,
    - Country, City, State, Region,
    - Product ID, Category, Sub-Category, Product Name,
    - Sales, Quantity, Profit, Returns, Payment Mode.

---

## 📁 Project Structure

| Folder/File | Description |
|-------------|-------------|
| `notebooks/` | Jupyter Notebooks with Python scripts for data cleaning for cleaning and EDA 
| `dashboards/` | Power BI dashboard files (.pbix), Images of dashboards, public link to access the interactive dashboard |
| `EDA_visuals/` | Visuals of trends created using matplotlib,seaborn |
| `README.md` | Project overview |
| `requirements.txt` | Python libraries used |

---

## 📊 Dashboards Overview

# 📈 Sales Dashboard
Objective: Provide a high-level overview of Amazon’s sales performance.

Visuals & Components:

KPIs: Total Sales, Total Profit, Total Quantity.

📉 Area Chart: Monthly trend of total sales

📊 Horizontal Bar Chart: Top 5 sub-categories by sales

📊 Clustered Bar Chart: Sales vs Profit by category

📈 Line Chart: Sales & Profit trend by states



# 📦 Product Dashboard
Objective: Analyze product-level performance across different filters.

Interactive Filters:

📅 Year and Month

🏷️ Category

Visuals:

📉 Waterfall Chart: Profit contribution by Region

📊 Bar Chart: Top-selling products by sales

🍩 Donut Chart: Orders by Segment (Consumer, Corporate, Home Office)

📈 Line Chart: Sales & Profit by Sub-Category

📊 Clustered Column Chart: Sales vs Profit by Region



# 👥 Customers Dashboard
Objective: Understand customer behavior and geographic distribution.

Interactive Filters:

🙋 Customer Name

Visuals:

📊 Bar Chart: Units Sold by Shipping Mode

🗺️ Revenue by State: Map or stacked chart

📈 Area Chart: Revenue by Customer over month

📍 Azure Map: Sales by City with interactive tooltips



## 🔍 Exploratory Data Analysis (EDA)

Performed using Python:
- Handled missing values and duplicates
- Visualized:
  - Product Category Distribution
  - Sales Distribution
  - Monthly Sales Trend
  - Sales vs Profit by Category

---

## 📌 Key Insights

- **Technology** and **Office Supplies** are top-performing categories.
- Profitability is higher in the **West** region.
- Seasonal spikes during Q4 (Nov-Dec).
- Certain sub-categories consistently underperform and can be optimized.

---

## 📦 Tech Stack

- **Python**: Data cleaning, transformation, and EDA using pandas, matplotlib, seaborn
- **Power BI**: Interactive dashboards for multi-dimensional analysis
- **Excel**:  Preliminary data inspection, quick pivots, and tabular summaries
- **Jupyter Notebooks**: Exploratory and analytical workflow
- **Git & GitHub** Version control and project sharing


## 📌 Conclusion
This Amazon Sales Analysis project provided a comprehensive view of sales performance across multiple dimensions—time, products, and customers. By leveraging Python for data exploration and Power BI for dashboarding, the project uncovered meaningful trends, performance drivers, and areas for improvement.

✅ Key Takeaways:

Consistent Seasonality: Sales and profit exhibited noticeable seasonal spikes, especially during Q4 (Nov–Dec), indicating strong holiday demand.

Product Insights: A few sub-categories drive the majority of revenue, while others contribute less profit and could be candidates for optimization.

Regional Trends: Sales and profitability vary significantly by region, with some underperforming areas requiring strategic attention.

Customer Behavior: Repeat customers and specific customer segments (like Corporate) tend to generate higher order volumes and revenue.

The interactive dashboards allow stakeholders to explore performance in real-time, empowering data-driven decision-making for:

- Inventory planning

- Regional targeting

- Product portfolio adjustments

- Marketing and promotions strategy



## 🙋‍♂️ Author

**Faizan Ali**  
Data Analyst | AWS Certified | Python | Power BI | SQL 
[LinkedIn](https://www.linkedin.com/in/faizan-ali-profile) • [GitHub](https://github.com/faizan-ali)

