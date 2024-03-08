# PizzaSales
 ## Problem Statements
 
 ### This dashbaord helps to understand  to analyze key indicates for pizza sales data to gain insights into company's business performance, specially we want to calculate the following metrics.
 
 ## KPI Requirements
 
#### 1.Total Revenue: The sum of the total price of all pizza orders.
#### 2.Average Order Value:The average amount spent per order. Calculated by dividing the total revenue by the total number od orders.
#### 3.Total Pizza Sold:The sum of the quantities of all pizza sold.
#### 4.Total Orders:The total number of order placed.
#### 5.Average pizza per order:The Average number of pizza sold per order.Calculated by the dividing the total number of pizza sold by the total number of orders.

## CHART Requirements

#### Visualize various aspects of the pizza sales data to gain insights and understand key trends.
#### 1.Daily Trend for Total orders
#### 2.Monthly Trend for Total orders
#### 3.Percentage of Sales by Pizza Category
#### 4.Percentage Sales by Pizza
#### 5.Total pizza sold by Pizza Category
#### 6.Top 5 Best Seller By Revenue,Total Quantity and Total Orders
#### 7.Bottom 5 Best Seller By Revenue,Total Qunatity and Total Orders

## SOFTWARE USED


### MS OFFICE / Excel
### MS SQL SERVER 19.0
### SQL SERVER MANAGEMENT STUDIO-19.0
### Version: 2.126.1261.0 64-bit (February, 2024)


### DATA SOURCE

#### Sales data : Primary data used for this analysis is the "pizza_sales.csv" file,conataining detailed information about each sale made by the company.

### Data Cleaning/Prepration
In the initial data prepration phase we performed the following task
1. Data loading and inspection
2. Handling missing value
3. Data cleaning and formatting.



### Data Analysis

include some interesting code/feature worked with

------ sql 
select DATENAME(MONTH, order_date) as Month_Name, COUNT(DISTINCT order_id) as Total_Orders
from pizza_sales
GROUP BY DATENAME(MONTH, order_date)------


## Result/Insights
The analysis results are summerized as follows,

  ### BUSIEST DAYS AND TIME
  
### 1.Orders are highest on weekend, Friday/Saturday evenings.
### 2.There are maximum orders from month of July and January.

### SALES PERFORMENCE

### 1.Classic category contributes to maximum Sales & Total orders.
### 2.Large Size pizza contributes to maximum Sales.

 ### BEST SELLERS

 ### REVENUE

  ### The Thai chicken Pizza contributes to maximum Revenue.

  ### QUANTITY
  
  ### The Classic Deluxe pizza contribute to maximum Total Quantities.

  ### TOTAL ORDERS

  ### The Classic Deluxe pizza contribute to maximum Total orders.

  ### WORST SELLERS

  ### REVENUE

  ### The Brie Carre Pizza contributes to minimum Revenue.

  ### QUANTITY

  ### The Brie Carre pizza contribute to minimum Total Quantities.

  ### TOTAL ORDERS

 ### The Brie Carre pizza contribute to minimum Total orders.
