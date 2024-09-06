# Restaurant Sales Project

## Project Overview

This project focuses on analyzing sales data to gain insights into trends, customer preferences, and transaction types. Using Python for data analysis and visualization, the project identifies patterns in sales performance to help inform better business decisions and future growth strategies. [here](https://github.com/Om-Kale/Restaurant_Sales/blob/main/Restaurant%20Sales_1.ipynb)
## PPT Presentation

I have created a detailed PowerPoint presentation that covers the key findings, insights, and visualizations from this project. You can view the presentation [here](https://publuu.com/flip-book/647451/1443851).

---

## Key Features

- **Sales Volume Analysis**: Breakdown of total items sold, most popular products, and transaction types.
- **Revenue Trends**: Visualization of transaction amounts over time.
- **Customer Insights**: Analysis of sales trends by time of day and customer preference.
- **Sales Forecasting**: Linear regression applied to forecast future trends.

---

## Challenges Faced

1. **Data Cleaning**:
   - The dataset had missing values in the `transaction_type` column, which needed to be addressed.
   - Some inconsistencies in the `time_of_sale` field were corrected to ensure accurate analysis.

2. **Time-Series Data**:
   - Handling and converting the date field into a usable format for time-series analysis presented challenges, especially in grouping data by month/year.

3. **Handling Non-Numeric Data**:
   - For plotting and modeling, categorical variables like `item_name` and `transaction_type` required encoding and proper formatting.

4. **Outliers**:
   - Outliers in transaction amounts were identified and treated to avoid skewing the analysis.

---

## How Business Problems Were Solved

### 1. **What are the most popular items sold?**
   - **Solution**: By visualizing the total number of items sold per category, we identified the top-performing products. Fast food items like Vadapav and Panipuri were found to be the most popular.

### 2. **When do customers tend to purchase more?**
   - **Solution**: Analyzing sales by time of day helped us see that evenings and nights had the highest sales volumes, allowing businesses to target peak hours for promotions.

### 3. **What payment method do customers prefer?**
   - **Solution**: Using visualizations of transaction types (cash vs. online), we found that a majority of customers preferred cash transactions, providing insights into possible payment method optimization.

### 4. **Are there any sales trends or seasonality patterns?**
   - **Solution**: Time-series analysis of sales data showed that certain months had higher transaction amounts, allowing the business to prepare better for peak seasons.

---

## Solutions Implemented

1. **Data Cleaning**:
   - Handled missing values and standardized time-related fields for more accurate analysis.

2. **Visualization**:
   - Created various visualizations such as bar charts, pie charts, and line plots to present key insights.

3. **Regression Analysis**:
   - Applied linear regression to analyze trends in transaction amounts over time for different item types.

4. **Sales Forecasting**:
   - Forecasted future sales based on past performance using time-series data.

---

## Plan / Next Steps

1. **Improving Customer Experience**:
   - Implement targeted promotions during peak hours to increase sales during slower times.
   - Offer discounts or rewards for using online payment methods to diversify transaction types.

2. **Product Portfolio Optimization**:
   - Based on item popularity, adjust the product offerings to focus on high-demand items while phasing out low-performing ones.

3. **Sales Prediction Enhancement**:
   - Continue refining the sales forecasting model by incorporating more variables like marketing spend, seasonal events, and customer demographics.

4. **Expand Dataset**:
   - Collect more data on customer behavior, feedback, and external factors to further enhance the accuracy of future predictions.

---



