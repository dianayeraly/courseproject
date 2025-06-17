# courseproject
This project showcases a fully interactive Power BI dashboard designed to demonstrate the use of time intelligence calculations. The goal is to provide stakeholders with dynamic insights into business performance over various time periods, leveraging the power of DAX (Data Analysis Expressions) and Power BI's visualization capabilities.
The **Time Intelligence Dashboard** helps users explore and compare key metrics over time, such as **Year-to-Date (YTD)**, **Month-to-Date (MTD)**, **Quarter-to-Date (QTD)**, and **Same Period Last Year (SPLY)** values. It is ideal for monitoring sales or operational data, detecting trends, and making timely decisions based on accurate, historical comparisons.

This dashboard project was developed as part of my training in data analytics and demonstrates my growing expertise in Power BI and DAX.

## Project Objectives

- Apply **time intelligence functions** to real-world scenarios.
- Develop **dynamic, period-based metrics** using DAX.
- Design a clean and user-friendly dashboard for business monitoring.
- Strengthen skills in **data modeling**, **measure creation**, and **interactive visualization**.
- Build a reusable template for business reporting with calendar-based logic.

## 🛠 Tools & Technologies Used

| Tool | Purpose |
|------|---------|
| **Power BI Desktop** | Data modelling, visualisation, and dashboard creation |
| **DAX (Data Analysis Expressions)** | Custom calculations for time-based metrics |
| **Calendar Table** | Supports time-based logic and allows date filtering |
| **Power Query** | Basic data transformation and preparation |
| **Slicers & Filters** | Interactivity and period selection |

## Key Features

### Time Intelligence Metrics
- **YTD (Year-to-Date)**: Calculates cumulative values from the start of the year to the selected date.
- **MTD (Month-to-Date)**: Measures performance from the beginning of the month.
- **QTD (Quarter-to-Date)**: Tracks cumulative results for the current quarter.
- **SPLY (Same Period Last Year)**: Enables direct year-over-year comparisons.

All metrics are implemented with dynamic DAX measures that update based on user input (e.g., slicers).

### Visualizations
- **Line Charts**: Display performance trends over time (e.g., monthly or quarterly).
- **KPI Cards**: Highlight key metrics (e.g., Total Sales, MTD Sales, YoY % Change).
- **Bar Charts**: Compare different periods (e.g., this year vs. last year).
- **Slicers**: Allow filtering by year, month, or custom date range.

### Data Model
- A separate **calendar table** is created with calculated columns for:
  - Year, Quarter, Month, Day
  - Month Name, Short Month
  - Sorting Indexes for correct chart order
- The calendar table is linked to the main data table using a **date relationship**, which enables accurate DAX calculations.

## File Contents

- **`Time intelligence 1.pbix`**  
  A Power BI report file that includes:
  - Time intelligence measures
  - Fully functional and styled dashboard
  - Custom visuals and slicers
  - Data model with calendar relationship

## Key Learning Outcomes

- Mastery of **basic time intelligence** in DAX using:
  - `TOTALYTD()`, `TOTALMTD()`, `TOTALQTD()`, `SAMEPERIODLASTYEAR()`
- How to structure a proper **calendar table** to enable time-based calculations
- Practical experience in building **responsive dashboards**
- Understanding how **filter context** and **relationships** affect calculations
- Hands-on experience in presenting **clean, decision-supporting visuals**

## Future Improvements

- Add financial metrics such as:
  - Profit, Cost, and Gross Margin
  - Forecasting using time series methods
- Implement **drill-through** and **bookmarking** features for deeper interactivity
- Connect to **live or streaming data sources** (e.g., SQL databases or APIs)
- Introduce **user-level filtering** and row-level security for scalable business use
- Expand with **geographic visuals** (e.g., regional sales maps)
