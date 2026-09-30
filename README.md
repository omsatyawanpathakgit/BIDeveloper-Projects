# Blinkit Grocery Sales Analysis Dashboard

An interactive Business Intelligence project built using Microsoft Power BI to analyze Blinkit's grocery sales performance.

The dashboard transforms raw grocery sales data into an interactive business dashboard containing KPIs, product-level analysis, outlet analysis, location analysis, and interactive filters.

## Project Overview

The project focuses on analyzing:

* Sales performance
* Product categories
* Outlet performance
* Outlet locations
* Outlet sizes
* Product fat content
* Customer ratings
* Item visibility
* Outlet establishment trends

The dashboard is designed to provide a consolidated view of business performance and support data-driven business analysis.

## Key Performance Indicators

The dashboard highlights four major KPIs:

| KPI             |  Value |
| --------------- | -----: |
| Total Sales     | $1.20M |
| Average Sales   |   $141 |
| Number of Items |     9K |
| Average Rating  |      4 |

These KPIs provide an overview of the overall sales and product performance.

## Dashboard Analysis

### 1. Total Sales by Outlet Establishment Year

The dashboard analyzes total sales according to the year in which outlets were established.

This helps analyze:

* Sales trends across establishment years
* Performance of older and newer outlets
* Changes in sales contribution over time

### 2. Sales by Item Type

Sales are analyzed across different product categories, including:

* Fruits and Vegetables
* Snack Foods
* Household
* Frozen Foods
* Dairy
* Canned Products
* Baking Goods
* Health and Hygiene
* Meat
* Soft Drinks
* Breads
* Hard Drinks

This helps identify product categories contributing significantly to overall sales.

### 3. Fat Content Analysis

Products are divided into:

* Low Fat
* Regular

The dashboard compares their contribution to overall sales.

### 4. Fat Content by Outlet Location

Fat-content sales are analyzed across:

* Tier 1
* Tier 2
* Tier 3

This provides insight into product preferences across different outlet locations.

### 5. Outlet Size Analysis

Sales are compared across:

* Small
* Medium
* High

This helps understand the relationship between outlet size and sales.

### 6. Outlet Location Analysis

Sales are compared across:

* Tier 1
* Tier 2
* Tier 3

The dashboard shows differences in sales contribution across outlet location tiers.

### 7. Outlet Type Analysis

Different outlet types are compared using:

* Total Sales
* Number of Items
* Average Sales
* Average Rating
* Item Visibility

This provides a broader view of outlet performance.

## Interactive Filters

The dashboard contains interactive filters for:

### Outlet Location Type

Analyze performance across different location tiers.

### Outlet Size

Compare sales and performance across outlet sizes.

### Item Type

Focus the analysis on individual product categories.

## Reset / Refresh Functionality

A reset control is included to return the dashboard to its default state after filters are applied.

## Business Questions Answered

The dashboard can answer questions such as:

1. What are the total and average sales?
2. Which product categories contribute the most sales?
3. How does sales performance differ by outlet location?
4. How does outlet size relate to sales?
5. How do Low Fat and Regular products compare?
6. How does sales performance vary by outlet establishment year?
7. Which outlet types contribute the most sales?
8. How many items are associated with different outlet types?
9. What is the average customer rating?
10. How does item visibility vary across outlet types?

## Project Workflow

```text
Raw Dataset
     |
     v
Data Import
     |
     v
Data Cleaning & Transformation
     |
     v
Power Query
     |
     v
Data Modeling
     |
     v
DAX Measures
     |
     v
KPI Creation
     |
     v
Dashboard Development
     |
     v
Interactive Filters
     |
     v
Business Analysis
```

## DAX Measures

### Total Sales

```DAX
Total Sales = SUM(Data[Sales])
```

### Average Sales

```DAX
Avg Sales = AVERAGE(Data[Sales])
```

### Number of Items

```DAX
No of Items = COUNTROWS(Data)
```

### Average Rating

```DAX
Avg Rating = AVERAGE(Data[Rating])
```

## SQL Analysis

The repository also contains SQL analysis resources:

```text
SQL Data and Doc (Use for SQL Analysis)/
```

This folder includes:

* BlinkIT Grocery Data.csv
* Blinkit Analysis.pptx
* Query Doc (1).docx
* blinkit.json

The SQL resources provide an additional way to analyze the same business dataset.

## Project Files

```text
Blinkit BI Project/
|
├── BlinkIT Grocery Data.xlsx
├── blinkit_dashboard.pbix
├── blinkit_dashboard_walkthroughVideo.mp4
├── background kpi.png
│
```

## Technologies Used

* Microsoft Power BI
* Power Query
* DAX
* Data Visualization
* Business Intelligence

## Skills Demonstrated

* Data Cleaning
* Data Transformation
* Data Modeling
* DAX
* KPI Development
* Interactive Dashboard Development
* Business Analysis
* Data Visualization
* Business Data Storytelling

## Author

**Om Satyawan Pathak**

Data Analytics | Business Intelligence | Data Science

Email: [omsatyawanpathakgit@gmail.com](mailto:omsatyawanpathakgit@gmail.com)

LinkedIn: https://www.linkedin.com/in/om-satyawan-pathak-029b02368
