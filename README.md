# Customer Behavior Analytics For Revenue Growth

An end-to-end Data Analytics project that analyzes retail customer shopping behavior using **Python, MySQL, and Power BI**. The project demonstrates the complete analytics workflow from data preprocessing and SQL-based business analysis to interactive dashboard development and business recommendations.

---

## Project Overview

Retail businesses generate large volumes of customer transaction data every day. This project transforms raw customer shopping data into meaningful business insights by analyzing purchasing patterns, customer demographics, subscription behavior, product performance, and revenue trends.

The objective is to support data-driven decision-making through data cleaning, SQL analysis, and interactive visualizations.

---

## Problem Statement

Analyze customer shopping behavior to identify purchasing trends, customer segments, revenue drivers, and product performance. Build an interactive dashboard and generate business recommendations that help improve customer engagement and overall business performance.

---

## Tech Stack

- **Python** – Data preprocessing and cleaning
- **Pandas** – Data manipulation
- **MySQL** – Database management and SQL analysis
- **Power BI** – Interactive dashboard and data visualization
- **Jupyter Notebook** – Development environment
- **Git & GitHub** – Version control and project hosting

---

## Dataset

The dataset contains customer shopping transactions with information such as:

- Customer ID
- Age
- Gender
- Item Purchased
- Product Category
- Purchase Amount
- Location
- Season
- Review Rating
- Shipping Type
- Subscription Status
- Discount Applied
- Previous Purchases
- Payment Method
- Purchase Frequency

---

## Project Workflow

### 1. Data Preprocessing (Python)

- Imported the dataset using Pandas
- Explored dataset structure
- Checked missing values
- Removed duplicate records
- Verified data types
- Created additional analytical columns (Age Group)
- Prepared clean data for SQL analysis

---

### 2. Database Integration (MySQL)

- Created a MySQL database
- Imported the cleaned dataset
- Created the customer table
- Verified imported records
- Connected Python with MySQL

---

### 3. SQL Business Analysis

Performed business analysis using SQL queries, including:

- Revenue by Gender
- High-Spending Customers Using Discounts
- Top Rated Products
- Shipping Type Comparison
- Subscriber vs Non-Subscriber Analysis
- Discount Usage Rate
- Customer Segmentation
- Top Products by Category
- Repeat Buyer Analysis
- Revenue by Age Group

---

### 4. Power BI Dashboard

Developed an interactive dashboard featuring:

- Total Revenue
- Total Customers
- Average Purchase Amount
- Average Review Rating
- Revenue by Product Category
- Revenue by Gender
- Revenue by Age Group
- Subscription Analysis
- Shipping Type Analysis
- Product Performance
- Interactive Slicers and Filters

---

## Key Insights

Some of the business questions answered in this project include:

- Which customer segment generates the highest revenue?
- How do subscribers compare with non-subscribers?
- Which products receive the highest customer ratings?
- Does shipping type influence customer spending?
- Which age group contributes the most revenue?
- How effective are discount campaigns?
- Which products perform best within each category?

---

## Business Recommendations

Based on the analysis, the following recommendations were identified:

- Strengthen customer loyalty programs.
- Promote subscription plans through exclusive benefits.
- Focus marketing campaigns on high-value customer segments.
- Maintain inventory for top-performing products.
- Offer personalized discount campaigns.
- Use interactive dashboards for continuous business monitoring.

---

## Dashboard Preview

> **Power BI Dashboard**

Add your dashboard image here.

```markdown
![Dashboard](dashboard/Customer%20Behavior%20Analysis%20Dashboard.png)
```

---

## Project Structure

```
Customer-Shopping-Behavior-Analysis/
│
├── data/
│   └── customer_shopping_behavior.csv
│
├── notebooks/
│   └── customer_behaviour_analysis.ipynb
│
├── sql/
│   └── customer_behaviour_analysis_sql_queries.sql
│
├── dashboard/
│   ├── Customer Behavior Analysis Dashboard.png
│   └── Customer_Shopping_Behavior.pbix
│
├── reports/
│   ├── Business_Problem_Statement.pdf
│   └── Customer Behaviour Analytics Report.pdf
│
├── presentation/
│   └── Customer Behaviour Analytics for Revenue Growth.pptx
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

## How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/Customer-Shopping-Behavior-Analysis.git
```

### 2. Navigate to the Project Directory

```bash
cd Customer-Shopping-Behavior-Analysis
```

### 3. Install Required Libraries

```bash
pip install -r requirements.txt
```

### 4. Open the Jupyter Notebook

Launch Jupyter Notebook and open:

```
notebooks/customer_behaviour_analysis.ipynb
```

Run all cells sequentially to perform data preprocessing and analysis.

### 5. Import Dataset into MySQL

- Create a database (e.g., `customer_behavior`)
- Import the cleaned CSV dataset into the `customer` table
- Execute the SQL queries available in the `sql` folder

### 6. Open the Power BI Dashboard

Open:

```
dashboard/Customer_Shopping_Behavior.pbix
```

Refresh the data source if required and explore the interactive dashboard.

---

## Future Enhancements

- Customer churn prediction using Machine Learning
- Sales forecasting
- Real-time dashboard integration
- Automated ETL pipeline
- Cloud deployment using Power BI Service

---

## Author

**Sangeetha**

Data Analytics | Python | SQL | Power BI

---

## License

This project is intended for educational and portfolio purposes.
