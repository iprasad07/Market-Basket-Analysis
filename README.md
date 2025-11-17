# Market-Basket-Analysis
As a data analyst, I developed an interactive Power BI dashboard to analyze market basket performance across multiple regions, identifying pricing strategies, regional sales patterns, and product performance metrics.
KPI Development
Designed and implemented key performance indicators:

Financial KPIs:

Total Actual Price (796K)
Total Sold Price (678K)
Total Loss/Discount Amount (118K)


Operational KPIs:

Number of Salespersons (510)
Geographic Coverage (35 Countries)
Average Discount Rate by Region


Performance Metrics:

Revenue per Salesperson by Region
Product-wise Price vs. Loss Analysis
Regional Market Share Percentages



3. Data Visualization
Created multiple chart types for comprehensive analysis:

Bar Charts:

Price and Loss per Item (dual-axis comparison)
Price and Loss by Region (clustered bar chart)


Pie Charts:

Amount per Region (revenue distribution)
Discount per Region (loss distribution)


Data Tables:

Regional Summary with calculated metrics
Salesperson count by region



4. Data Transformation (Power Query)
Performed ETL operations:

Cleaned and standardized regional data
Created hierarchies (Region → Country → Item)
Aggregated transaction-level data
Removed duplicates and handled missing values
Created calculated columns for derived metrics

5. Interactive Dashboard Features
Implemented user-friendly elements:

Cross-filtering between visualizations
Drill-down capabilities by Region → Country → Product
Dynamic titles with DAX measures
Conditional formatting for performance indicators
Slicers for Region, Item, and Country filtering

6. Business Intelligence Analysis
Conducted comprehensive analysis revealing:

EMEA as the dominant region (45% market share)
High discount rates indicating competitive pricing pressure
Top 3 products (Refrigerator, Washing Machine, Air Conditioner) driving 60%+ revenue
Salesperson efficiency varying from 1,103 to 1,457 per person across regions
