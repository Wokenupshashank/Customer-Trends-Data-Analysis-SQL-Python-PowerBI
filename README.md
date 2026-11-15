<div align="center">

# 📊 Customer Behavior & Retail Analytics

### From raw retail transactions to actionable business insight

An end-to-end analytics project combining **Python**, **SQL**, and **Power BI** to explore customer behavior, sales trends, product performance, and retention.

[Project workflow](#-project-workflow) · [Key questions](#-business-questions) · [Run locally](#-getting-started) · [Repository files](#-repository-files)

</div>

---

## 📌 Project overview

Understanding how customers shop helps retailers make better decisions about marketing, inventory, and customer retention. This project takes retail transaction data through a complete analytics workflow: data preparation and exploratory analysis in Python, deeper analysis in SQL, and interactive reporting in Power BI.

The result is a practical, stakeholder-oriented view of customer segments, purchasing patterns, and business performance.

## 🧰 Tools and technologies

| Area | Tools |
| --- | --- |
| Data preparation & exploration | Python, Pandas, NumPy, Matplotlib, Seaborn |
| Database & analysis | SQL — MySQL, PostgreSQL, or SQL Server |
| Business intelligence | Power BI, DAX, data modeling |
| Version control | Git and GitHub |

## 🔄 Project workflow

### 1. Data preparation and EDA · Python

- Handle missing values, standardize formats, and remove duplicate records.
- Explore distributions, outliers, and initial patterns in customer demographics and spending.
- Engineer analysis-ready features, including customer lifetime value and transaction recency.
- Load the cleaned data into a relational database.

### 2. Deep-dive analysis · SQL

- Organize cleaned data into tables suited to analytical queries.
- Use joins, common table expressions (CTEs), and window functions to investigate business questions.
- Compare customer groups, category performance, and purchasing behavior.

### 3. Interactive reporting · Power BI

- Build a star-schema model connecting fact and dimension tables.
- Create DAX measures for KPIs such as year-to-date sales, retention rate, and profit margins.
- Explore results with interactive filters for geography, time period, and customer segment.

## 📈 Business questions

The analysis focuses on questions such as:

- Which customer demographics have the highest average order value (AOV)?
- How does month-over-month revenue change across product categories?
- How is loyalty status related to purchase frequency?
- Which seasons show higher or lower purchasing activity?
- Which product categories perform best or need attention?
- Which customers may be at risk of churn based on the time between purchases?

## 📊 Areas of analysis

- **Customer segmentation** — group customers by demographics and purchasing behavior.
- **Sales trends** — identify seasonal peaks and slower periods to inform inventory planning.
- **Product performance** — compare category performance.
- **Churn and retention** — examine purchase gaps to identify customers who may be at risk.

## 🚀 Getting started

### Prerequisites

- Python and Jupyter Notebook
- A local SQL server (MySQL, PostgreSQL, or SQL Server)
- Power BI Desktop

### 1. Clone the repository

```bash
git clone https://github.com/Wokenupshashank/Customer-Trends-Data-Analysis-SQL-Python-PowerBI.git
cd Customer-Trends-Data-Analysis-SQL-Python-PowerBI
```

### 2. Prepare the data

Open `Customer_Shopping_Behavior_Analysis.ipynb` in Jupyter Notebook and run the cells to import, clean, and explore the data. The notebook's final cell connects to a local SQL instance and loads the cleaned data. Configure the connection details for your environment before running it.

### 3. Run the SQL analysis

Start your SQL server, then open `customer_behavior_sql_queries.sql` in a compatible SQL client, such as DBeaver, SQL Server Management Studio, or MySQL Workbench. Run the queries to explore the analysis results.

### 4. Open the dashboard

Open `customer_behavior_dashboard.pbix` in Power BI Desktop. Update its data source settings to use your local database, then refresh the model.

## 📂 Repository files

| File | Description |
| --- | --- |
| `Business Problem Document.pdf` | Project scope and business objectives |
| `Customer Shopping Behavior Analysis.pdf` | Final analytical report |
| `Customer_Shopping-Behavior-Analysis.pptx` | Stakeholder presentation |
| `Customer_Shopping_Behavior_Analysis.ipynb` | Python data preparation and exploratory analysis |
| `customer_behavior_sql_queries.sql` | SQL analysis queries |
| `customer_behavior_dashboard.pbix` | Power BI dashboard |
| `customer_shopping_behavior.csv` | Raw transactional dataset |
| `LICENSE` | MIT License |

## 📜 License

This project is licensed under the [MIT License](LICENSE). You are welcome to use and adapt it in accordance with the license terms.
