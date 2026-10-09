
# E-Commerce Sales, Customer and Delivery Performance Analysis

## 1. Project Overview

This project analyzes e-commerce sales, customer behavior, and delivery performance using Python and Power BI.

The objective is to identify sales trends, high-revenue product categories, customer segments, and delivery performance to support business decisions.

## 2. Project Objectives

- Analyze sales and revenue performance.
- Identify top-performing product categories.
- Analyze customer segments and purchasing behavior.
- Compare revenue across sales channels, payment methods, and devices.
- Evaluate delivery status and shipping time.
- Develop interactive Power BI dashboards.

## 3. Dataset Information

- Domain: E-Commerce Analytics
- Total Records: 10,000
- Original Columns: 15
- Analysis Period: 20 April 2024 to 19 April 2025

The dataset includes order details, customer IDs, product IDs, product categories, prices, quantities, order dates, shipping dates, payment methods, sales channels, device types, and delivery statuses.

## 4. Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Microsoft Power BI
- Power Query
- DAX
- Google Colab

## 5. Data Cleaning and Preparation

- Checked missing values and duplicate records.
- Handled missing numerical values using median imputation.
- Replaced missing categorical values with "Unknown".
- Standardized inconsistent category and text values.
- Converted date columns into the correct format.
- Created a revenue column using price multiplied by quantity.
- Created a shipping days column using shipping date and order date.
- Removed shipping and billing address columns from the Power BI analysis.

After cleaning, the dataset contained 10,000 rows and 17 columns.

## 6. Exploratory Data Analysis

Python was used to perform exploratory data analysis using 10 visualizations:

1. Product Category Distribution
2. Revenue Distribution
3. Quantity Distribution
4. Shipping Days Distribution
5. Revenue by Product Category
6. Revenue by Customer Segment
7. Price vs Quantity
8. Correlation Heatmap
9. Pairplot Analysis
10. Category and Customer Segment Revenue Analysis

## 7. Power BI Dashboards

### Dashboard 1: Sales and Revenue Performance

- Total Revenue
- Total Orders
- Average Order Value
- Revenue by Product Category
- Monthly Revenue Trend
- Revenue by Customer Segment
- Revenue by Payment Method
- Revenue by Sales Channel
- Revenue by Device Type

### Dashboard 2: Customer and Delivery Performance

- Average Shipping Days
- Delivered Orders
- Delivery Rate
- Orders by Customer Segment
- Monthly Order Trend
- Orders by Device Type
- Delivery Status Distribution
- Average Shipping Days by Delivery Status
- Orders by Payment Method

Both dashboards include interactive slicers for data exploration.

## 8. Key Insights

1. Total revenue was approximately $5.59 million across 10,000 orders.
2. Average Order Value was $558.60.
3. Toys generated the highest category revenue at approximately $941,109.89.
4. VIP customers generated approximately $2.75 million in revenue.
5. Returning customers generated approximately $2.34 million in revenue.
6. The Social sales channel generated approximately $1.43 million in revenue.
7. A total of 6,844 orders were delivered.
8. The delivery rate was 68.44%.
9. Average shipping time was 4.01 days.
10. The correlation between price and quantity was approximately -0.02.

## 9. Business Recommendations

- Prioritize high-revenue product categories.
- Improve retention among VIP and Returning customers.
- Monitor and optimize Social channel campaigns.
- Encourage New customers to make repeat purchases.
- Monitor Pending and Returned orders.
- Track shipping time and delivery status regularly.

## 10. Conclusion

This project demonstrates an end-to-end data analytics workflow using Python and Power BI. Data cleaning, exploratory analysis, and interactive dashboards helped identify important patterns in revenue, customer behavior, product categories, sales channels, and delivery performance.

The findings can support business monitoring and data-driven decision-making.

## 11. Skills Demonstrated

- Data Cleaning and Preprocessing
- Exploratory Data Analysis
- Python Data Analysis
- Data Visualization
- Power BI Dashboard Development
- DAX Measures
- Business Insights
- Data-Driven Decision-Making
