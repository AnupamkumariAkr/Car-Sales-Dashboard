# CAR-SALES-DASHBOARD

## ABOUT COMPANY
Our company, a car dealership, aims to enhance sales performance tracking and analysis through an efficient Car Sales Dashboard in Tableau.

## OBJECTIVE
Design and develop a dynamic, interactive Car Sales Dashboard to visualize critical KPIs, enabling data-driven decision-making and understanding sales performance trends over time.

## PROBLEM STATEMENT 1: KPI’s  REQUIRENMENT
### SALES OVERVIEW: 
- Year-to-Date (YTD) Total Sales
- Year-over-Year (YOY) Growth in Total Sales


- ### AVERAGE PRICE ANALYSIS:
- YTD Average Price
- YOY Growth in Average Price
  

- ### CARS SOLD METRICS:
- YTD Cars Sold
- YOY Growth in Cars Sold


## PROBLEM STATEMENT 2: CHARTS REQUIRENMENT
1. **YTD Sales Weekly Trend:** Display a line chart illustrating the weekly trend of YTD sales. The X-axis should represent weeks, and the Y-axis should show the total sales amount.
2. **YTD Total Sales by Body Style:** Visualize the distribution of YTD total sales across different car body styles using a Pie chart.
3. **YTD Total Sales by Color:** Present the contribution of various car colors to the YTD total sales through a pie chart.
4. **YTD Cars Sold by Dealer Region:** Showcase the YTD sales data based on different dealer regions using a map chart to visualize the sales distribution geographically.
5. **Company-Wise Sales Trend in Grid Form:** Provide a tabular grid that displays the sales trend for each company. The grid should showcase the company name along with their YTD sales figures.
6. **Details Grid Showing All Car Sales Information:** Create a detailed grid that presents all relevant information for each car sale, including car model, body style, color, sales amount, dealer region, date, etc.

## DATA AVAILABLE
### CAR DATA:
- Car ID
- Date
- Customer Name
- Gender
- Annual Income
- Dealer Name
- Company
- Model
- Engine
- Transmission
- Color
- Price ($)
- Dealer No
- Body Style
- Phone
- Dealer Region


###  CALENDER TABLE(CREATED): 
- Date
- Month
- Week
- Year

 ###  DASHBOARD:
   
![Dashboard 1 (2)](https://github.com/AnupamkumariAkr/Car-Sales-Dashboard/assets/157566167/fdd317c4-e987-45e6-81d0-96a5ec380785)


**PROBLEM STATEMENT 1: KPI’s**

**SALES OVERVIEW :**
- **YTD Total Sales:** $371.19M
    - **Formula:** `SUM('Car Data'[Total Sales])`
- **YOY Growth in Total Sales:** 23.6%
    - **Formula:** `[Sales Difference]/[PTYD Total Sales]`


**AVERAGE PRICE ANALYSIS:**
- **YTD Average Price:** $27.99k
    - **Formula:** `TOTALYTD([Avg Price],'Calendar Table'[Date])`

- **YOY Growth in Average Price:** -0.79%
    - **Formula:** `[Avg Price Diff]/[PTYD Avg Price]`



**CARS SOLD METRICS :**
- **YTD Cars Sold:** 13.26K
    - **Formula:** `SUM('Car Data'[YTD Car Solds])`

- **YOY Growth in YTD Car sold:**24.57%




 ## Done by
   - Anupam kumari
