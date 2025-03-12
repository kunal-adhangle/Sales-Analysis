# Sales Data Analysis - Power BI Project

## Project Overview

This Power BI project focuses on analyzing sales data to derive meaningful insights. The dataset is sourced from an Excel file and has been utilized to create various visualizations that help in understanding sales performance, trends, and regional distributions.

## Dataset Information

**Source**: Excel File (Sales Data Analysis.xlsx)

### Data Fields:
- Order ID  
- Date  
- Customer Name  
- Product  
- Category  
- Region  
- Quantity  
- Cost Price  
- Selling Price  
- Discount  
- Sales  
- Profit  
- Net Sales  

## Power BI Features Implemented

### Data Cleaning & Transformation
- Handled missing values and duplicates.  
- Transformed data for better visualization and analysis.  

### Visuals Used
- **Card Visual**: To display key metrics like Total number of orders.  
- **Filters**: Applied to slice and dice the data based on different attributes.  
- **Map Visual**: Used to represent sales distribution across different regions.  
- **Column Chart**: Showcases sales performance over time.  
- **Scatter Plot**: Represents the relationship between profit and sales.  
- **Bar Chart**: Displays product-wise top and bottom profit.  
- **Line Chart**: Highlights sales trends over time.  

### Edit Interactions
- Enabled interaction between different visuals to allow a dynamic data exploration experience.
- 1st Date Visual will only filter on top product bar chart visual and 2nd date visual will only on bottom product bar chart viual

### DAX Measure Created
```DAX
Sum Sales = SUM('Fact Sheet'[Net Sales])
```
This measure calculates the total sales from the dataset.

## Insights Derived
- Identified top-performing regions based on sales figures.  
- Analyzed trends in sales and profit over time.  
- Observed the impact of discounts on sales performance.  
- Product-wise sales performance analysis.  

## Power BI Service Dashboard 
<img width="958" alt="Screenshot 2025-03-12 064520" src="https://github.com/user-attachments/assets/4b6874f2-e3a1-4b1e-8495-0f8c3a231cfe" />

## Power BI Desktop
<img width="959" alt="Screenshot 2025-03-12 064625" src="https://github.com/user-attachments/assets/6455df9d-e3b6-41b2-88b5-f99114472355" />

