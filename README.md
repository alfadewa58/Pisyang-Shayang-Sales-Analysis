
# Pisyang Shayang Sales Analysis

![alt text](https://github.com/alfadewa58/Empowering-Data-Driven-Decisions-for-a-Global-Bike-Company-With-BI-Dashboard/blob/main/Screenshot%202025-01-20%20164210.png)

[View the Dashboard](https://app.powerbi.com/view?r=eyJrIjoiZTg1MWYyOTQtNTk0OC00MzIzLTg0NGMtNDJhNjg0MGRhNWFhIiwidCI6IjUwODkxNmEwLTdiODktNDNhMS1hZjRlLTcyZmUxNWFiYTViOSIsImMiOjEwfQ%3D%3D&embedImagePlaceholder=true&pageName=1f93fdf6704b7571d979)


## **Business Overview**

**Pisyang Shayang** is a food and beverage (F&B) company specializing in fried bananas (**pisang goreng**) with a variety of creative toppings. The company targets a young audience and families, leveraging both online platforms such as Gojek, Shopee, and Grab, as well as offline sales channels.

## **Problem Statement**

### 1. Sales Patterns
   - **When are the peak and low sales periods throughout the year?**
   - **Are there months with high potential that haven't been fully optimized?**
   - **What is the sales growth over time?**

### 2. Price Increase Impact
   - **How did the price increase in July/August 2024 affect revenue?**
   - **What is the comparison of revenue before and after the price increase?**
   - **Did the number of units sold decrease significantly after the price increase?**

### 3. Sales Channel Diversification
   - **Which sales channels contribute the most to overall sales?**
   - **What is the breakdown of sales by product size (small vs large)?**
   - **Is there any monthly variation in these proportions?**

## **Goals**

1. **Improve Sales Efficiency and Strategy**
   - Identify months with high sales potential for major promotional campaigns.
   - Minimize low season sales with targeted marketing strategies.
   
2. **Analyze the Price Increase Impact**
   - Ensure that the price increase does not significantly reduce revenue.

3. **Optimize Sales Channel Diversification**
   - Identify which sales channels need more focus or development.
   - Understand customer preferences based on product size to tailor stock and promotions accordingly.

## **Analysis Components**

### 1. **Sales (pcs)**

   - **Highest and Lowest Sales**:
     - Identify the months with the highest and lowest sales.
   
   - **High Potential Month & Low Potential Month**:
     - Analyze months with potential to optimize promotions and sales strategies.
   
   - **Sales Growth**:
     - Calculate sales growth on a month-to-month or year-to-year basis.

### 2. **Revenue Analysis**

   Premise: In July/August 2024, a price increase was implemented. This analysis aims to understand the impact on revenue:

   - **Pre- and Post-Price Increase**:
     - Compare average/total sales before and after the price increase to determine if revenue increased despite a potential decrease in unit sales.
   
   - **Revenue Efficiency**:
     - Calculate the number of units needed to achieve a certain revenue before and after the price increase. Did the price increase make the company more efficient in generating revenue?

### 3. **Sales Channel Diversification**

   - **Sales Channel Contribution**:
     - Identify the contribution of each sales channel (Gojek, Shopee, Grab, QRIS, offline) to total sales each month and calculate averages.

   - **Sales by Product Size**:
     - Analyze sales by product size (small vs large). Are there any trends in customer preferences?
   
   - **Monthly Breakdown**:
     - Break down the sales diversification by month before averaging to gain deeper insights.

## **Optimization of Sales in December (High Season)**

### **Recommendations**:
   - **End-of-Year Discount**: Offer 20-30% off all products from December 20-31.
     - **Large Products**: 30% off (to drive sales).
     - **Small Products**: 20% off (to maintain margins).
   
   - **Bundling Promotions**:
     - "Buy 5 Small, Get 1 Large Free."
     - "Extra 10% off for purchases over Rp100,000."
   
   - **Cashback Voucher**: Provide a cashback of Rp10,000 for purchases over Rp75,000 through Shopee.

## **Data Source**

This analysis uses data from the **Pisyang Shayang Cashier App**, which includes transaction records, sales data, product details, and sales channel information.

## **Data Columns**:

- **Transaction ID**: Unique identifier for each transaction.
- **Date**: Date of the transaction.
- **Sales Channel**: The platform used for the sale (e.g., Gojek, Shopee, Grab, QRIS, Offline).
- **Product Size**: The size of the product (Small, Large).
- **Quantity Sold**: Number of units sold.
- **Revenue**: Total revenue from the transaction.
- **Price**: Price per unit at the time of sale.
- **Discounts**: Any discounts applied to the transaction.

## **Technologies Used**

- **Python** for data analysis and visualization.
- **Pandas** for data manipulation and analysis.
- **Matplotlib** and **Seaborn** for data visualization.
- **Jupyter Notebook** for analysis and reporting.

## **Next Steps**

1. Conduct a detailed analysis of sales patterns across months.
2. Compare revenue before and after the price increase in July/August 2024.
3. Identify the best sales channels and customer preferences based on product size.
4. Implement recommended strategies for improving December sales.
