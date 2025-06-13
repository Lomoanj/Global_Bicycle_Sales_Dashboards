# Global_Bicycle_Sales_Dashboard 📊🚲✨

---

## Table of Contents 📑

* [Project Overview](#project-overview-)
* [Key Features of the Project](#key-features-of-the-project-)
* [Key Insights Gained](#key-insights-gained-)
* [Technologies Used](#technologies-used-section)
* [Data Source](#data-source-)
* [Visualizations & Dashboards](#visualization-section)
    * [Raw Data (Excel) Snippet](#raw-data-excel-snippet-)
    * [Excel Dashboard Highlights](#excel-dashboard-highlights-)
    * [Power BI Data Model](#power-bi-data-model-)
    * [Power BI Dashboard Highlights](#power-bi-dashboard-highlights-)
    * [Tableau Data Model](#tableau-data-model-)
    * [Tableau Dashboard Highlights](#tableau-dashboard-highlights-)
* [SQL Code Highlights](#sql-code-highlights-)
    * [Example 1: Calculating Total Sales by Product Category](#example-1-calculating-total-sales-by-product-category)
    * [Example 2: Identifying Top 10 Customers by Revenue](#example-2-identifying-top-10-customers-by-revenue)
* [How to View the files](#how-to-view-the-files-)
* [License](#license-)
* [Contact](#connect)


---

## Project Overview 💡

This repository showcases a comprehensive **Business Intelligence (BI) project** dedicated to analyzing the global sales performance of **Adventure Works Cycles**, a prominent multinational bicycle manufacturer. Our core mission was to transform raw sales data into powerful, actionable insights through interactive dashboards. The ultimate goal? To strategically drive **market expansion**, optimize **customer targeting**, and achieve significant **operational cost reductions**.

---

## Key Features of the Project 🚀

* **Comprehensive Dashboard Suite:** We developed dynamic and intuitive dashboards using **Excel**, **Tableau**, and **Power BI**. These dashboards offer powerful interfaces for diverse data exploration and engaging stakeholders.
* **Multi-Platform Data Preparation & Modeling:**
    * We leveraged **MySQL** for robust data cleaning, transformation, and complex joins across the 8 distinct Excel datasets, creating a structured analytical base.
    * Further individual data modeling and connections were then set up independently *within* **Excel**, **Power BI**, and **Tableau** to optimize dashboard performance and meet specific reporting needs.
    * Initial data manipulation and analysis were also performed directly in **Excel**.
* **Cross-Functional Reporting:** The solution provides insights relevant to various business areas, including sales, product management, and regional operations.
* **Easy-to-Follow Analysis Steps:** We laid out clear and simple steps, from bringing in the raw data to creating the final dashboards. This makes the entire analysis transparent and easy for anyone to understand and repeat.

---

## Key Insights Gained 🧠✨

Through in-depth analysis of Adventure Works Cycles' sales data, we uncovered the following key insights:

* **Top-Performing Product Categories & Regions:** We identified which specific bicycle product lines and geographical markets (North America, Europe, Asia) contributed most significantly to overall sales and revenue. This helps pinpoint areas of success and those needing attention.
* **Customer Segmentation & Value:** Our analysis provided a clear understanding of different customer segments and the characteristics of high-value customers. This is crucial for guiding targeted marketing and sales strategies.
* **Sales Trend & Seasonality Analysis:** We discovered patterns in sales over time, including significant seasonal fluctuations and long-term growth trends. These insights are vital for more accurate forecasting and inventory management.
* **Potential Operational Cost Drivers:** We pinpointed specific areas within the supply chain and manufacturing processes (e.g., related to subcomponent shipments from the Mexico plant) that present valuable opportunities for cost optimization.
* **Market Share Opportunities:** Our findings highlighted specific areas where expanding product availability or focusing sales efforts could lead to a substantial increase in market share.

---

<a name="technologies-used-section"></a>
## Technologies Used 🛠️

* **Microsoft Excel:** 📊 We used Excel as the initial raw data source, working with 8 distinct datasets. It was also utilized for preliminary data manipulation and the creation of some dashboards.
* **MySQL:** 🐘 This was our primary tool for robust data cleaning, transformation, and integrating disparate datasets through complex joins, building a structured analytical base.
* **Tableau Public:** 📈 We developed highly interactive and visually appealing dashboards using the free **Tableau Public Desktop application** for in-depth data visualization and exploration.
* **Microsoft Power BI Desktop:** 📊 We leveraged Power BI to create compelling reports and dashboards, utilizing its powerful data modeling and reporting capabilities.

---

## Data Source 📁

The foundation of this project utilized 8 distinct Excel files containing historical sales data from **Adventure Works Cycles**. These specific datasets are included directly within this repository for easy access and reproducibility.

* **Project Data Files:** You can find the Excel datasets used in this project, click here: [Data](https://github.com/Lomoanj/Global_Bicycle_Sales_Dashboards_/tree/main/DataSets)
* For reference, the original AdventureWorks sample database from Microsoft (from which these datasets are derived) can be found at:
    * [Microsoft SQL Server Samples - AdventureWorks on GitHub](https://github.com/Microsoft/sql-server-samples/releases/tag/adventureworks)
* A comparable community-contributed dataset in Excel format can also be found on Kaggle:
    * [AdventureWorks2022 - Excel Format (.xlsx) on Kaggle](https://www.kaggle.com/datasets/tituspr/adventureworks2022-excel-format)

---

<a name="visualization-section"></a>
# Visualizations & Dashboards 🖼️✨

Explore the key insights and interactive dashboards developed for this project. Screenshots of the data and final dashboards are provided below.  

---

### Raw Data (Excel) Snippet 📂📊
A glimpse of the initial data structure from one of the Excel files, highlighting its raw format before extensive transformation. This shows the starting point of our analysis.

![Raw Data](https://github.com/user-attachments/assets/cdf28bb0-dcc6-400c-b0d4-70e405d69f87)

---

### Excel Dashboard Highlights 📈📑
We also developed insightful dashboards directly within Excel, showcasing preliminary analysis and key metrics that provided foundational understanding.
![Excel sales](https://github.com/user-attachments/assets/dd7a2535-a657-4cba-9180-87611f22a2f2)
![Excel Profit](https://github.com/user-attachments/assets/c9396d09-99ab-4236-9664-1ac895e69f46)
![Excel Product](https://github.com/user-attachments/assets/037d4c8c-a0a0-40cd-9341-35daecbf9c7a)

---

### Power BI Data Model 🔗📊
A screenshot illustrating the data model built in Power BI Desktop, showcasing the relationships and structure established between the imported tables for effective analysis.
![PowerBI Model](https://github.com/user-attachments/assets/5565d7ac-9b55-49c1-95fe-14606260b0f9)

---

### Power BI Dashboard Highlights 📈⭐
Interactive reports built in Power BI, showcasing key insights such as sales trends, customer segments, and regional performance. These dashboards leverage Power BI's powerful data modeling and visualization capabilities.
![PowerBI 1](https://github.com/user-attachments/assets/20a9bf79-b00a-4bcf-8c01-1f8c9f81c5dc)
![PowerBI 2](https://github.com/user-attachments/assets/4148a254-f4ed-4688-a33e-0a52708c0ec5)
![PowerBI 3](https://github.com/user-attachments/assets/d07fc092-1a7e-4468-93a6-910e0950337e)
![PowerBI 4](https://github.com/user-attachments/assets/2d8e56cb-f281-4c65-b5c8-0b8181711a69)

---

### Tableau Data Model 🔗📊
A screenshot illustrating the data model built in Tableau, showcasing the relationships and structure established between the imported tables for effective analysis.
![Tableau Model](https://github.com/user-attachments/assets/d3d2f218-6234-492a-9242-aa839ae56048)

---

### Tableau Dashboard Highlights 📈✨
Dynamic and exploratory dashboards created in Tableau, providing a deeper dive into product profitability, market share, and other key performance indicators.
![Tableau 1](https://github.com/user-attachments/assets/51e8a973-a2d1-4970-a603-33fdcc51b11a)
![Tableau 2](https://github.com/user-attachments/assets/d3bfd8d5-ac78-4e02-92cb-c7ea729cebf2)
![Tableau 3](https://github.com/user-attachments/assets/49a6c726-3096-4897-8376-788d4b75177c)

---
## SQL Code Highlights 💾👨‍💻

Here are a few illustrative SQL queries and snippets used for data cleaning, transformation, and aggregation within MySQL. These demonstrate key operations performed to prepare the data for visualization. Full scripts covering database schema creation and ETL processes can be found in the `SQL_Scripts/` directory.

### Example 1: Calculating Total Sales by Product Category
This query aggregates sales data to show total revenue for each product category, helping identify top-performing product lines and inform product strategy.
```sql
SELECT
    pc.Name AS ProductCategory,
    SUM(sod.OrderQty * sod.UnitPrice) AS TotalSales
FROM
    Sales.SalesOrderDetail AS sod
JOIN
    Production.Product AS p ON sod.ProductID = p.ProductID
JOIN
    Production.ProductSubcategory AS psc ON p.ProductSubcategoryID = psc.ProductSubcategoryID
JOIN
    Production.ProductCategory AS pc ON psc.ProductCategoryID = pc.ProductCategoryID
GROUP BY
    pc.Name
ORDER BY
    TotalSales DESC;
```
### Example 2: Identifying Top 10 Customers by Revenue
This snippet helps in identifying the most valuable customers based on their total revenue contribution, which is crucial for targeted marketing and customer retention efforts.
```sql
SELECT
    c.CustomerID,
    p.FirstName,
    p.LastName,
    SUM(soh.TotalDue) AS TotalRevenue
FROM
    Sales.SalesOrderHeader AS soh
JOIN
    Sales.Customer AS c ON soh.CustomerID = c.CustomerID
JOIN
    Person.Person AS p ON c.PersonID = p.BusinessEntityID
GROUP BY
    c.CustomerID, p.FirstName, p.LastName
ORDER BY
    TotalRevenue DESC
LIMIT 10;
```

---

## How to View the Files 👀

Want to explore the project's data, dashboards, or code? Here's how to access them directly within this repository:

1.  **Excel Data & Dashboards:**
    * View the raw Excel datasets directly here: [Data Files](https://github.com/Lomoanj/Global_Bicycle_Sales_Dashboards_/tree/main/DataSets)
    * For Excel dashboards, find the relevant files here: [Excel Dashboards](https://github.com/Lomoanj/Global_Bicycle_Sales_Dashboards_/blob/main/Excel%20Analysis.xlsm)
    * **GitHub's built-in viewer** will allow you to preview these `.xlsx` files directly in your browser without needing to download them.

2.  **Power BI Dashboards:**
    * Access the Power BI files directly here: [Power BI Dashboards](https://github.com/Lomoanj/Global_Bicycle_Sales_Dashboards_/blob/main/PowerBI_Analytics.pbix)
    * Download the .pbix file from this directory and open them using **Power BI Desktop** on your computer.

3.  **Tableau Dashboards:**
    * Access the Tableau files directly here: [Tableau Dashboards](https://github.com/Lomoanj/Global_Bicycle_Sales_Dashboards_/blob/main/Tableau_Analytics.twbx)
    * Download the .twbx (packaged workbook) file from this directory and open them with **Tableau Public** on your computer.

4.  **SQL Scripts:**
    * Browse all the SQL files directly here: [SQL Scripts](https://github.com/Lomoanj/Global_Bicycle_Sales_Dashboards_/blob/main/MySQL%20Queries.sql)
    * **GitHub's code viewer** allows you to read the scripts directly in your browser. You can copy the code from here to execute in your MySQL environment.

---

## License 📜

This project is open-sourced under the **MIT License**. For more details, please see the [LICENSE](LICENSE) file in this repository.

---
<a name="connect"></a>
## Connect with Me! 👋

* **LinkedIn:** [linkedin.com/in/lomoanj](https://www.linkedin.com/in/lomoanj/)
* **GitHub:** [github.com/Lomoanj](https://github.com/Lomoanj)
* **Email:** [lomoanj@gmail.com](mailto:your.lomoanj@gmail.com)

---
