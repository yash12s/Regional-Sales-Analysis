# Regional Sales Analysis

This is an end-to-end Data Analytics project to analyze regional sales data using Python, MySQL, and Power BI. The aim is to extract meaningful business insights, visualize patterns, and present findings using interactive dashboards.

## Project Overview

 **Tools Used:** Python (Pandas, Matplotlib, Seaborn), Power BI
 **Skills Demonstrated:** Data Cleaning, EDA, Visualization, Business Insight Generation
 **Dataset:** Sales data with 64,000+ records including product, customer, location, revenue, and profit details.

##  Key Steps in the Project

### 1. Data Cleaning (Python)
- Checked for null values
- Parsed order_date as datetime
- Filtered dataset for year-wise analysis

### 2. Feature Engineering
- Created new columns like:
  - total_cost = order_quantity × cost
  - profit = revenue - total_cost
  - profit_margin_pct

### 3. Exploratory Data Analysis
- Monthly Sales Trend (Line Chart)
- Overall Seasonality across years
- Top & Bottom Products by Revenue
- Sales by Channel (Pie Chart)
- Order Value Distribution
- State-wise Revenue & Order Count
- Average Profit Margin by Channel
- Customer Segmentation by Revenue vs Profit Margin
- Correlation Heatmap

### 4. Power BI Dashboard
- Developed an interactive dashboard showing:
  - Regional performance
  - Channel-wise trends
  - Customer & product insights

##  Final Deliverables

- Regional_Sales_Analysis.ipynb → Python Analysis & Visualizations
- Regional_Sales_Dashboard.pbix → Power BI Dashboard File

## How to Run

1. Clone the repository
2. Run the `.ipynb` notebook in Jupyter/Colab
3. Open `.pbix` file in Power BI Desktop for dashboard
 
