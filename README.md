
# AdventureWorks Sales Dashboard




https://github.com/user-attachments/assets/9c10dd25-78cf-4b08-8ac2-effe7df042de




**Interactive Power BI Dashboard connected directly to SQL Server**


## Overview
This project transforms SQL Server data into a fully interactive and insightful Power BI dashboard.  
It was my first end-to-end dashboard project, where I handled everything from data extraction and cleaning to modeling and designing visual analytics.  

The main goal was to create a **user-friendly, interactive dashboard** for the AdventureWorks sales data that allows stakeholders to explore trends, performance, and product insights effortlessly.

---

## Project Steps

### Data Preparation
- Connected SQL Server data to Power BI using direct query and import methods.
- Cleaned and transformed data using Power Query for accurate analysis.
- Handled missing values, duplicates, and created calculated columns for key metrics.

### Data Modeling
- Designed a Star Schema to optimize reporting and relationships.
- Created hierarchies (Product & Date) for intuitive drill-down and analysis.
- Developed DAX measures: Number of Orders, Total Due, Subtotal, Tax, Freight.
- Used `USERELATIONSHIP` to compare Order Date, Ship Date, and Due Date in a single visual for better time analysis.

### Visuals & Interactivity
- Line Chart with drill-down to explore trends over time.
- Drill Through pages for detailed product insights.
- Donut & Bar Charts to highlight Total Due across categories.
- Matrix comparing Total & Canada Sales per Territory per Year.
- Q&A Visual allowing users to ask natural language questions and get instant visual results.
- Custom Tooltips to display Max Quantity per group when hovering over points.

### Slicers & Navigation
- Territory & Year slicers synced across multiple pages.
- Bookmarks to toggle visibility of certain charts for cleaner navigation.
- Ensured all visuals were interactive and easy to explore for non-technical users.

---

## Challenges & Solutions
- **Challenge:** Linking multiple date fields (Order, Ship, Due) for meaningful comparisons.  
  **Solution:** Used `USERELATIONSHIP` in DAX to switch context dynamically in visuals.
- **Challenge:** Presenting large datasets interactively without performance lag.  
  **Solution:** Optimized data model with Star Schema and minimized complex calculations.

---

## Outcome & Impact
- Dashboard became **fully interactive, intuitive, and easy to use** for stakeholders.
- Enabled analysis of:
  - Geographic distribution of orders
  - Sales trends and growth over years
  - Top-performing products and categories
  - Group-level performance comparisons
- Improved decision-making and strategic planning for sales operations.
- Strengthened my skills in **Power BI, SQL Server, Data Modeling, and Analytical Thinking**.

---

## Technologies
- **Power BI** – Interactive dashboards and visualizations  
- **SQL Server** – Data extraction and queries  
- **DAX & Data Modeling** – Calculated measures and relationships  
- **Data Visualization & Analytics** – Charts, slicers, and reporting best practices  

---


This experience enhanced my understanding of Power BI, data modeling, and interactive reporting. I’m excited to continue building impactful dashboards in the future.
