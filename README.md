# Customer Shopping Behavior Analysis 📊

## 📌 Project Overview

Customer Shopping Behavior Analysis is a data analytics project focused on understanding customer purchasing patterns, preferences, spending habits, and subscription behavior.

The project analyzes **3,900 customer purchase records** using Python, PostgreSQL, and Power BI to uncover meaningful business insights and support data-driven decision-making.

## 🎯 Project Objectives

- Analyze customer purchasing and spending patterns.
- Identify customer segments based on purchase history.
- Understand the impact of discounts and subscriptions on purchasing behavior.
- Identify top-rated and frequently purchased products.
- Analyze revenue across different customer demographics.
- Develop business recommendations to improve customer engagement and loyalty.

## 🛠️ Tech Stack

- **Programming Language:** Python
- **Data Analysis:** Pandas, NumPy
- **Database:** PostgreSQL
- **Query Language:** SQL
- **Data Visualization:** Power BI
- **Dashboard Calculations:** DAX
- **Dataset:** CSV

## 📂 Dataset Overview

The dataset contains:

- **Total Records:** 3,900
- **Total Columns:** 18
- **Missing Values:** 37 values in the Review Rating column.

### Key Features

- Customer demographics: Age, Gender, Location.
- Purchase details: Item Purchased, Category, Purchase Amount.
- Shopping behavior: Discount Applied, Promo Code Used, Previous Purchases.
- Customer preferences: Subscription Status, Review Rating, Shipping Type.
- Product details: Season, Size, Color.

## 🐍 1. Data Cleaning & Exploratory Data Analysis using Python

Used Python and Pandas to prepare the dataset for analysis.

Key activities:

- Imported and explored the dataset using Pandas.
- Examined dataset structure and summary statistics.
- Handled missing Review Rating values using the median rating of each product category.
- Standardized column names using snake_case.
- Created an `age_group` column through feature engineering.
- Created a `purchase_frequency_days` column.
- Removed the redundant `promo_code_used` column after checking its relationship with `discount_applied`.
- Connected Python to PostgreSQL and loaded the cleaned dataset.

## 🗄️ 2. SQL Analysis using PostgreSQL

Performed SQL-based business analysis to answer important questions about customer behavior.

Key analyses included:

1. Revenue comparison between male and female customers.
2. Identification of high-spending customers who used discounts.
3. Top 5 products based on average review ratings.
4. Comparison of average purchase amounts across shipping types.
5. Spending and revenue comparison between subscribers and non-subscribers.
6. Identification of products with the highest discount usage.
7. Customer segmentation into New, Returning, and Loyal customers.
8. Identification of the top 3 products within each category.
9. Analysis of repeat buyers and subscription behavior.
10. Revenue contribution across different age groups.

### SQL Concepts Used

- Aggregate Functions
- GROUP BY and ORDER BY
- Subqueries
- Common Table Expressions (CTEs)
- CASE Statements
- Window Functions
- ROW_NUMBER()

## 📊 3. Power BI Dashboard

Developed an interactive Power BI dashboard to present customer shopping insights.

### Dashboard Highlights

- Total number of customers.
- Average purchase amount.
- Average product review rating.
- Customer subscription distribution.
- Revenue and sales by product category.
- Revenue and sales by age group.
- Interactive filters for gender, category, shipping type, and subscription status.

### Key Dashboard Metrics

| Metric | Value |
|---|---:|
| Total Customers | 3.9K |
| Average Purchase Amount | $59.76 |
| Average Review Rating | 3.75 |

### DAX

Used DAX measures to calculate and display important dashboard metrics and KPIs.

## 🔍 4. Key Business Insights

- Female customers generated slightly higher total revenue than male customers in the analyzed dataset.
- Express shipping customers had a higher average purchase amount than standard shipping customers.
- Loyal customers represented the largest customer segment.
- Discounts influenced purchasing patterns across several product categories.
- Customer subscription behavior provided opportunities for improving retention.
- Different age groups contributed to overall revenue.

## 💡 5. Business Recommendations

- **Boost Subscriptions:** Promote exclusive benefits for subscribers.
- **Customer Loyalty Programs:** Reward repeat buyers to improve customer retention.
- **Targeted Marketing:** Focus on high-revenue customer segments.
- **Product Positioning:** Highlight top-rated and popular products in marketing campaigns.
- **Discount Optimization:** Review discount policies to balance sales growth and profitability.

## 📁 Project Structure

```text
Customer-Behavior-Analysis/
│
├── Customer_Shopping_Behavior_Analysis.ipynb
├── customer_shopping_behavior.csv
├── customer_behavior_sql_queries.sql
├── customer_behavior_dashboard.pbix
├── Customer Shopping Behavior Analysis.pdf
├── Business Problem Document.pdf
├── Customer-Shopping-Behavior-Analysis.pptx
│
└── README.md
```

## 🚀 How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/swayamkumar4/Customer-Behavior-Analysis.git
cd Customer-Behavior-Analysis
```

### 2. Install Python dependencies

```bash
pip install pandas numpy jupyter
```

### 3. Run the Jupyter Notebook

```bash
jupyter notebook
```

Open `Customer_Shopping_Behavior_Analysis.ipynb` and execute the cells.

### 4. PostgreSQL Setup

- Install and configure PostgreSQL.
- Create a database.
- Configure the database connection in the notebook.
- Execute the SQL queries from `customer_behavior_sql_queries.sql`.

### 5. Open Power BI Dashboard

- Open `customer_behavior_dashboard.pbix` using Power BI Desktop.
- Configure the data source if required.
- Refresh the dataset and explore the interactive dashboard.

## 👨‍💻 Author

**Swayam Kumar Patro**

GitHub: [@swayamkumar4](https://github.com/swayamkumar4)

---

⭐ If you find this project useful, feel free to explore the repository!
