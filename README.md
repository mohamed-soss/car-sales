# Car Sales Dashboard Project

## Overview

This project features a comprehensive **Car Sales Dashboard** developed using Microsoft Power BI, designed to provide actionable insights into car sales performance across various dimensions. The dashboard was last updated on May 21, 2025, at 6:51 PM EEST, and serves as a powerful tool for business analysts, sales managers, and stakeholders to monitor key performance indicators (KPIs), identify trends, and make data-driven decisions.

The dashboard integrates multiple data sources to present a holistic view of sales metrics, including year-to-date (YTD) and month-to-date (MTD) sales figures, average prices, and sales distributions by body style, color, region, and company. It includes interactive filters and detailed data tables for in-depth analysis.

---

## Features

### 1. Key Performance Indicators (KPIs)
The dashboard prominently displays the following KPIs at the top for a quick overview of sales performance:

- **YTD Total Sales**: $371.2M
- **MTD Total Sales**: $70.8M (with a 23.39% increase compared to the previous period)
- **YTD Average Price**: $28.0K (down by 0.79% from the previous period)
- **YTD Cars Sold**: 13.3K units
- **MTD Cars Sold**: 2.6K units (with a 24.57% increase compared to the previous period)

These metrics provide a snapshot of overall sales performance, highlighting both growth and areas of concern, such as the slight decline in average price.

### 2. Visualizations
The dashboard includes several visualizations to facilitate a deeper understanding of the data:

- **YTD Sales Weekly Trend**:
  - A line graph illustrating weekly sales trends over the year, with a peak reaching $14M.
  - This visualization helps identify seasonal patterns and sales fluctuations.

- **YTD Total Sales by Body Style**:
  - A donut chart categorizing sales by body style, including SUV, Hatchback, Sedan, Pickup, and Hardtop.
  - This breakdown allows stakeholders to understand which vehicle types are driving the most revenue.

- **YTD Total Sales by Color**:
  - A donut chart showing the distribution of sales by color, specifically Pale White, Black, and Red.
  - This visualization highlights customer color preferences, which can inform inventory decisions.

- **YTD Cars Sold by Dealer Region**:
  - A geographical map of the United States, with bubbles representing sales volume in key regions such as Plano, Aurora, Scottsdale, and others.
  - This map enables regional performance analysis, identifying high-performing and underperforming areas.

- **Company-wise Sales Trend**:
  - A detailed table comparing sales metrics across multiple companies, including Acura, Audi, BMW, Cadillac, Chrysler, and Ford. The table includes:
    - **YTD Average Price**: Ranges from $28.7K (Ford) to $29.4K (Acura).
    - **YTD Cars Sold**: Ranges from 370 units (Acura) to 886 units (Ford).
    - **YTD Total Sales**: Ranges from $19.3M (Acura) to $25.4M (Ford).
    - **% YTD Total Sales**: Contribution to overall sales, with Ford at 6.7% and Acura at 2.5%.
  - This comparison helps benchmark performance across brands and identify market leaders.

### 3. Interactive Filters
The dashboard includes a robust filtering system on the left-hand side, allowing users to drill down into specific subsets of the data:

- **Body Style**: Filter by SUV, Hatchback, Sedan, Pickup, Hardtop, or All.
- **Dealer Name**: Select specific dealers to analyze their performance.
- **Transmission**: Filter by transmission type (e.g., Automatic, Manual, or All).
- **Engine**: Filter by engine type (e.g., specific engine configurations or All).

These filters enable dynamic exploration of the data, allowing users to focus on specific segments of interest.

### 4. Detailed Data Table (Details Page)
The "Details" tab provides a granular view of the data in a tabular format, with the following columns:

- **Car ID**: Unique identifier for each car (e.g., CND_000001).
- **Date**: Transaction date (e.g., January 02, 2022).
- **Customer Name**: Name of the buyer (e.g., Geraldine, Gia).
- **Dealer Name**: Name of the dealership (e.g., Buddy Storbeck’s Diesel Service Inc, C & M Motors Inc).
- **Company**: Car manufacturer (e.g., Ford, Cadillac, Toyota).
- **Color**: Car color (e.g., Black, Red, Pale White).
- **Model**: Car model (e.g., Expedition, Eldorado, Celica).
- **Total Sales**: Sale amount for each transaction (e.g., $26.0K, $51.5K).

This table allows for detailed record-level analysis, supporting use cases such as auditing, customer profiling, and sales tracking.

---

## Technical Details

### Tool Used
- **Microsoft Power BI**: The dashboard was created using Power BI, a leading business intelligence tool, leveraging its robust visualization and data modeling capabilities.

### Data Sources
The dashboard integrates data from two primary tables:
- **Calendar Table**: Contains date-related information for time-based analysis.
- **Car Data Table**: Includes detailed transactional data such as car ID, customer details, dealer information, and sales figures.

### Development Environment
- The dashboard was developed in Power BI Desktop, as indicated by the interface (e.g., Home, Insert, Modeling tabs).
- It includes features like "Build Visual," "Filters," and "Data" panes for creating and customizing visualizations.

### Last Update
- The dashboard was last saved on **May 21, 2025, at 6:51 PM EEST**, ensuring the data and visualizations are up-to-date as of that timestamp.

---

## Usage
This dashboard can be used by:
- **Sales Managers**: To monitor overall sales performance, track regional and company-wise trends, and identify opportunities for growth.
- **Business Analysts**: To perform in-depth analysis using filters and detailed data tables, uncovering insights into customer preferences and market dynamics.
- **Executives**: To gain a high-level overview of KPIs and make strategic decisions based on sales trends and performance metrics.

The interactive nature of the dashboard allows users to explore the data at various levels of granularity, from high-level summaries to individual transactions.

---

## Future Enhancements
- **Predictive Analytics**: Incorporate machine learning models to forecast future sales trends based on historical data.
- **Additional Filters**: Add filters for more dimensions, such as customer demographics or sales channels.
- **Real-time Data Integration**: Enable real-time data updates to provide the most current insights.
- **Custom Visuals**: Introduce more advanced visualizations, such as heatmaps or treemaps, to enhance data exploration.

---

## Contact
For questions, feedback, or contributions to this project, please reach out via GitHub Issues or contact the project maintainer directly.
