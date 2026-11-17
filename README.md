# SQL & Tableau Data Analytics Projects

A collection of data analytics projects developed using SQL Server, SQL, Microsoft Excel, and Tableau. These projects demonstrate practical experience in data exploration, data preparation, SQL querying, calculated fields, and interactive dashboard development.

## Projects Overview

This repository contains two data analytics projects:

### 01. Student Depression Analysis | SQL & Tableau

An exploratory data analysis project focused on examining student-related factors and their distribution across the dataset.

**Tools Used:**
- Microsoft SQL Server
- SQL
- Tableau
- CSV

**Dataset:** Student Depression Dataset

**SQL Operations:**
- Database and table creation.
- Gender distribution analysis.
- Standardizing gender values from Female/Male to F/M.
- Age distribution analysis.
- Creating an `Age_Group` column using CASE statements.
- Exploring academic pressure and study satisfaction.
- Analyzing sleep duration and dietary habits.
- Examining study hours and financial stress.
- Exploring family history of mental illness.
- Converting the Depression column from BIT to VARCHAR.
- Replacing binary depression values with YES/NO.
- Creating an identity-based index column.

**Tableau Visualizations:**

The Student Count Analysis dashboard includes:

- Academic Pressure & Student Count.
- Financial Stress & Student Count.
- Sleep Duration & Student Count.
- Study Hours & Student Count.
- Study Satisfaction & Student Count.

**Project Files:** `01-Student-Depression-Analysis/`

---

### 02. Superstore Sales Analysis | Tableau

An interactive retail sales analysis project using the Sample Superstore dataset to explore sales performance, profitability, regional contributions, and order trends.

**Tools Used:**
- Tableau Desktop
- Microsoft Excel
- Tableau Calculated Fields

**Dataset:** Sample Superstore Sales Dataset

**Dashboard Visualizations:**

- **Profit by Region & Customer Segment:** Examines profit distribution across geographical regions and customer segments.
- **Sales Contribution by Region:** Shows the percentage contribution of different regions to total sales.
- **Profit vs Sales:** Explores the relationship between sales and profitability.
- **Order Quantity by Month:** Displays monthly order quantity trends.

**Calculated Fields:**

A custom calculated field named `Grouping Based on Unit Price` was created to categorize products into three groups:

- Group A: Unit Price less than or equal to 2,500.
- Group B: Unit Price greater than 2,500 and less than or equal to 5,000.
- Group C: Unit Price greater than 5,000.

An interactive filter was also created using the calculated field.

**Project Files:** `02-Superstore-Sales-Analysis/`

---

## Technologies & Skills

| Technology | Application |
|---|---|
| SQL Server | Database management and data preparation |
| SQL | Data exploration, transformation and aggregation |
| Tableau | Interactive dashboards and visualizations |
| Microsoft Excel | Dataset handling |
| CSV | Structured data storage |

## Repository Structure

```text
SQL-and-Tableau-Data-Analytics-Projects/
│
├── 01-Student-Depression-Analysis/
│   ├── Dataset/
│   ├── SQL/
│   ├── Tableau/
|   └── Screenshots/
│
├── 02-Superstore-Sales-Analysis/
│   ├── Dataset/
│   ├── Tableau/
│   └── Screenshots/
│
└── README.md
```

## How to Run the Projects

### Student Depression Analysis

1. Download the student dataset.
2. Import the CSV file into Microsoft SQL Server.
3. Execute the SQL script for data preparation and analysis.
4. Open the Tableau workbook.
5. Update the SQL Server connection to match your local database configuration.
6. Explore the Student Count Analysis dashboard.

### Superstore Sales Analysis

1. Download the Sample Superstore dataset.
2. Open the packaged Tableau workbook (`.twbx`) using Tableau Desktop.
3. Reconnect the data source if required.
4. Explore the dashboard and interact with the available filters.

## Key Learning Outcomes

- Working with structured datasets.
- Writing SQL queries for data exploration.
- Applying GROUP BY and aggregate functions.
- Using CASE statements for data categorization.
- Performing data type conversions and updates.
- Creating calculated fields in Tableau.
- Developing interactive dashboards.
- Analyzing business and student-related data patterns.
- Communicating analytical findings through visualizations.

## Notes

- The Student Depression Analysis project is exploratory and does not establish causation or provide clinical assessments.
- The student Tableau workbook uses a local SQL Server connection, which must be configured on another machine.
- The Superstore project includes a packaged Tableau workbook (`.twbx`) with an embedded data extract.

## Author

**Sagaljot Singh**

---

If you find these projects useful, feel free to star this repository.
