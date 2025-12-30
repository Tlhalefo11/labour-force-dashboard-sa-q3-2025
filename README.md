# labour-force-dashboard-sa-q3-2025
Power BI dashboard analyzing South Africa’s labour force data (Q3 2025)

Labour Force Characteristics Dashboard – South Africa (Q3 2025)

Project Overview:

This project presents an interactive Power BI dashboard analyzing South Africa’s labour force (ages 15–64) using Quarter 3, 2025 data from Statistics South Africa. The goal was to transform complex, unstructured survey data into a clean analytical model and derive insights across provinces, population groups, and sex.

Data Preparation & Transformation (Power Query):

The original dataset was provided in a wide, multi-header format, making it unsuitable for direct analysis. The following transformation steps were performed- Removed metadata and header rows. Filled down province labels to align with population groups, Separated province names from population group values, Standardized column names for clarity Unpivoted labour force measures into a tidy (long) format Cleaned and categorized sex values into Male and Female, Handled null values without distorting original totals. All transformations were completed using Power Query (ETL).

Dashboard Features & Insights:

The final dashboard enables users to-
Compare Economically Active vs Not Economically Active populations
Analyze labour force distribution by province, Examine employment status by population group. Filter results dynamically using slicers. View headline labour force figures using KPI cards

Key Observations:

Economically active populations are concentrated in major provinces
Clear disparities exist across population groups
Gender-based labour participation patterns are visible through interactive filtering

Tools Used:

Power BI Desktop – Data modeling & visualization
Power Query – Data cleaning and transformation
Statistics South Africa (Stats SA) – Source data

Project Files:

Labour_Force_Dashboard_Q3_2025.pbix – Power BI dashboard file
README.md – Project documentation

Purpose:

This project Work with real-world, messy datasets. Perform end-to-end data preparation. Build interactive dashboards for policy and economic analysis
