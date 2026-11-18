https://drive.google.com/drive/folders/1FQywJq7wdB_fNqa2uu88WxMWa7gFEK4y?usp=drive_link
https://archive.ics.uci.edu/dataset/352/online+retail?

Due to the large file sizes, both the original and cleaned datasets have been uploaded to Google Drive, as they exceed GitHub's file upload limitations. The Google Drive link, along with a direct download link for the datasets, has been provided in the README file for easy access.

# E-Commerce Sales Analysis – Power BI Dashboard

## 1. Project Overview

This project focuses on analysing online retail sales data using Microsoft Excel and Power BI. The aim is to understand sales performance, product trends, customer behaviour and geographical sales distribution through interactive dashboards.

## 2. Project Aim

To clean, analyse and visualise online retail sales data to identify business trends, understand customer and product performance, and provide useful insights to support business decisions.

## 3. Dataset Information

- **Dataset:** Online Retail Sales Dataset
- **Source:** Online Retail dataset
- **Format:** Excel
- **Main fields:** InvoiceDate, InvoiceNo, CustomerID, Description, Quantity, UnitPrice, Country, Sales Amount and Sales Category.

The dataset contains online retail transaction information, including products purchased, quantities, prices, customers and countries.

## 4. Tools and Technologies

- Microsoft Excel – Data cleaning and preparation
- Microsoft Power BI Desktop – Data modelling and visualisation
- Power Query – Data transformation and data type checking
- DAX – Creating calculated measures
- GitHub – Project documentation

## 5. Data Cleaning and Preparation – Excel

The original dataset was prepared in Excel before importing it into Power BI.

The preparation process included reviewing the dataset, checking the data structure, identifying data quality issues and preparing the cleaned file for analysis.

The cleaned Excel dataset was saved separately and used as the source for the Power BI report.

## 6. Data Import and Modelling – Power BI

The cleaned Excel file was imported into Power BI Desktop.

The required columns and data types were checked using Power Query. Sales Amount was set as a decimal number and Sales Category was set as text. The Sales Category column quality check showed no errors.

The following DAX measures were created:

- Total Sales
- Total Orders
- Total Quantity
- Total Customers

Total Sales was calculated by multiplying Quantity by UnitPrice and summing the results. Total Orders and Total Customers were calculated using distinct counts of InvoiceNo and CustomerID respectively.

The total sales measure was checked against the Excel total, approximately **9,748,131.07**.

## 7. Dashboard Development and Visualisation

An interactive Power BI report was developed with four pages.

### Page 1 – Sales Overview

- KPI cards: Total Sales, Total Orders, Total Quantity and Total Customers.
- Monthly Sales Trend – Line chart.
- Top 10 Products by Sales – Bar chart.
- Sales by Country – Map.
- Sales Contribution by Category – Waterfall chart.

The waterfall chart was selected because it presents positive sales contributions and the negative effect of returns more clearly than the donut chart initially tested.

### Page 2 – Product Performance Analysis

- Quantity Sold by Category – Bar chart.
- Sales by Category – Column chart.
- Product Performance table.
- Product Sales and Quantity Relationship – Scatter chart.
- Product-Level Sales Distribution – Treemap.

### Page 3 – Customer & Geographic Analysis

- Unique Customers by Country – Bar chart.
- Sales Contribution by Country – Treemap.
- Customer Status Distribution – Donut chart.
- Customer Distribution Across Countries – Map.
- Customer Sales & Purchase Details – Table containing CustomerID, Sales Amount and Quantity.

### Page 4 – Insights & Recommendations

This page summarises the purpose of the analysis and presents key business recommendations relating to product performance, customer behaviour and geographical sales activity.

## 8. Interactive Features and Dashboard Design

The following features were included:

- Country and Year slicers.
- Clear All Slicers button.
- Page Navigator buttons on all four pages.
- Consistent background colours and purple headings.
- Clear chart titles and organised layouts.

The navigation buttons were tested in Power BI Desktop using Ctrl + click.

## 9. Key Business Insights and Recommendations

The dashboard helps explore:

- Overall sales and order performance.
- Product categories contributing to sales.
- Relationships between product quantities and sales values.
- Customer distribution across countries.
- Geographical sales contribution.
- Monthly changes in sales performance.

**Recommendations:**

- Monitor product category performance to identify growth opportunities.
- Focus marketing efforts on countries with strong customer presence and sales activity.
- Review monthly sales trends when planning stock.
- Use customer and product analysis to support business decisions.

## 10. Conclusion

This project helped develop practical skills in Excel data preparation, Power Query, DAX calculations and Power BI visualisation.

The final report presents online retail sales information through four interactive pages, combining KPI cards, charts, maps, tables, slicers and navigation buttons.

The project demonstrates the complete data analytics process, from preparing the dataset to presenting meaningful business information through an interactive Power BI dashboard.

## 11. Project Files

The GitHub repository includes or will include:

- Original and cleaned Excel datasets.
- Power BI report (.pbix).
- Dashboard screenshots.
- Project documentation (README.md).

---

**Project Topic:** E-Commerce Sales Analysis

**Main Tools:** Microsoft Excel | Power BI | Power Query | DAX
