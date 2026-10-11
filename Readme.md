# 🛒 Supermarket Sales Analysis Dashboard

An interactive sales analytics dashboard developed using **Microsoft Power BI Desktop** to analyze supermarket transactions, compare branch performance, identify top-performing product lines, and understand customer and payment patterns.

## 📌 Project Overview

The Supermarket Sales Analysis Dashboard transforms raw transaction data into meaningful visual insights using data preparation, KPI analysis, and interactive visualizations.

This project was developed as part of the **Data Analytics using Power BI Internship at Scholars’ Minds, Tirupati**.

## 🎯 Objectives

- Analyze overall supermarket sales performance.
- Calculate key performance indicators (KPIs).
- Compare sales across product lines and branches.
- Examine monthly sales trends.
- Analyze customer types and payment methods.
- Enable interactive data exploration using slicers.
- Practice data cleaning, transformation, and visualization using Power BI.

## 🛠️ Tools and Technologies

- Microsoft Power BI Desktop
- Power Query Editor
- CSV dataset
- GitHub for project hosting and documentation

## 📂 Repository Structure

```text
Supermarket-Sales-Analysis/
│
├── README.md
│
├── data/
│   └── supermarket_sales.csv
│
├── dashboard/
│   └── Supermarket_Sales_Dashboard.pbix
│
└── screenshots/
    └── sales_dashboard.png
```

## 📊 Dataset Information

**Dataset file:** `supermarket_sales.csv`

**Dataset source:** [Supermarket Sales Dataset – GitHub](https://github.com/deepakorani/Supermarket-Sales-Kaggle-Dataset/blob/main/supermarket_sales.csv)

The dataset contains **1,000 transactions and 17 attributes**, covering supermarket sales from January to March 2019.

### Key attributes

| Attribute | Description |
|---|---|
| Invoice ID | Unique transaction identifier |
| Branch | Supermarket branch identifier |
| City | City where the branch is located |
| Customer type | Member or Normal customer |
| Gender | Customer gender |
| Product line | Product category |
| Unit price | Price per unit |
| Quantity | Number of units purchased |
| Tax 5% | Tax amount |
| Total | Total transaction amount, including tax |
| Date | Transaction date |
| Time | Transaction time |
| Payment | Payment method |
| cogs | Cost of goods sold |
| gross margin percentage | Gross margin percentage |
| gross income | Gross income from the transaction |
| Rating | Customer rating |

The dataset is used for educational and analytical purposes. Please refer to the original source for its applicable usage and attribution terms.

## 📈 Dashboard Features

The dashboard contains the following visualizations and interactive components:

### 1. Key Performance Indicators

- **Total Sales:** Overall transaction value.
- **Total Transactions:** Number of distinct invoices.
- **Total Quantity Sold:** Total quantity of products sold.
- **Total Gross Income:** Aggregate gross income.

### 2. Sales Analysis

- **Sales by Product Line:** Compares sales across six product categories.
- **Sales by Branch:** Compares performance across Branches A, B, and C.
- **Monthly Sales Trend:** Displays sales from January to March 2019.

### 3. Customer and Payment Analysis

- **Customer Type Analysis:** Compares Member and Normal transactions.
- **Payment Method Analysis:** Examines transactions made using Ewallet, Cash, and Credit Card.

### 4. Interactive Filters

- City slicer
- Branch slicer
- Date slicer

These filters allow users to explore the data based on selected locations, branches, and date ranges.

## 🔍 Key Findings

The completed dashboard displays the following overall results:

| KPI | Value |
|---|---:|
| Total Sales | $322,966.75 |
| Total Transactions | 1,000 |
| Total Quantity Sold | 5,510 |
| Total Gross Income | $15,379.37 |

Additional observations from the dashboard:

- **Food and Beverages** recorded the highest sales among the six product lines, at approximately $56,144.84.
- **Branch C** recorded the highest sales among the three branches, at approximately $110,568.71.
- January recorded approximately $116,291.87 in sales, followed by $97,219.37 in February and $109,455.51 in March.
- Normal customers accounted for 501 transactions, while Members accounted for 499 transactions.
- Ewallet recorded 345 transactions, Cash recorded 344, and Credit Card recorded 311.

These findings describe the supplied dataset and should not be interpreted as conclusions about all supermarket operations.

## 🚀 How to Use the Project

1. Clone or download this repository.
2. Navigate to the `dashboard/` folder.
3. Open `Supermarket_Sales_Dashboard.pbix` using Microsoft Power BI Desktop.
4. If prompted, update the CSV file path or reconnect the data source to `data/supermarket_sales.csv`.
5. Refresh the data if required.
6. Use the City, Branch, and Date slicers to explore the dashboard interactively.

**Requirement:** Microsoft Power BI Desktop must be installed to open and interact with the `.pbix` file.

## 🧹 Data Preparation

The dataset was prepared using Power Query Editor. The preparation process included:

- Inspecting column headers and data types.
- Assigning suitable types to categorical, numerical, date, and time columns.
- Converting dates using the appropriate regional format.
- Loading the prepared data into Power BI Desktop for analysis.

## 🎓 Learning Outcomes

This project provided practical experience in:

- Data cleaning and transformation using Power Query.
- Building KPI cards and interactive visualizations.
- Aggregating and comparing sales data.
- Analyzing trends and category-level performance.
- Creating slicers for interactive reporting.
- Organizing and documenting an analytics project using GitHub.

## 👨‍💻 Author

**Jinka Guru Sasank**

B.Tech – Computer Science and Engineering  
NBKR Institute of Science and Technology, Vidyanagar

**Internship Domain:** Data Analytics using Power BI  
**Organization:** Scholars’ Minds, Tirupati

---

*Developed as an internship project to demonstrate practical skills in data analytics, business intelligence, and interactive dashboard development.*