<div align="center">
  <h1>Kinetix Ventures Sales Data Analysis & Dashboard Report</h1>
  <img width="200px" src="https://raw.githubusercontent.com/blackcrowX/blackcrowX.github.io/main/images/icons/ms_excel.png"/>
</div>

This project utilized Microsoft Excel for comprehensive data cleaning, transformation, analysis, and visualization on a Kaggle sales dataset. The goal was to derive actionable insights by answering specific business questions and creating an interactive dashboard. The report outlines the entire process, from data preparation to the final dashboard, with key insights highlighted at each step.

## Skills Utilized
- Data Cleaning
- Data Transformation
- Data Analysis
- Visualization
- Statistical Analysis
- Excel Functions & Formulas


## Introduction

In this project, I worked on a sales dataset using Microsoft Excel to perform data cleaning, transformation, analysis, and visualization. The goal was to derive actionable insights from the dataset by answering specific business questions and creating an interactive dashboard. This report outlines the entire process, from data cleaning to the final dashboard, with relevant details at each step.


**Project Author:** [Jibrin Tijjani Isiaka](https://github.com/Adnanisme)

## Objective

The main objectives of this project were:

1. To clean and prepare the 2022 Kinetix Ventures sales data for analysis
2. To perform in-depth analysis of the sales data to answer key business questions
3. To create visualizations that effectively communicate the insights derived from the data
4. To develop an interactive dashboard that allows stakeholders to explore the data dynamically
5. To provide actionable recommendations based on the analysis findings


## Dataset

The dataset provided from  [kaggle.com](https://kaggle.com) contains various columns such as:

- Order ID
- Date
- Product
- Category
- Purchase Price
- Sale Price
- Profit
- Quantity
- Order Status
- Delivery Date & Time
- Delivery Cost
- Revenue
- Salesperson
- Customer Information (Name, Gender, Age, State, Country)

## Data Preparation

Data Cleaning Process

Before performing any analysis, I began with cleaning the dataset. Key cleaning tasks included:

1. Removing inconsistencies: For example, I found discrepancies in the product names, such as "sandals" with both correct and incorrect spellings. I used Excel's "Find and Replace" feature to ensure uniformity.

![366966613-9a7723b5-6a17-43df-aa23-6a1ae1e441df](https://github.com/user-attachments/assets/45fd2b03-6088-4a9e-8e37-cd4366d56fc8)

2. Standardizing Gender Values: I replaced inconsistent entries in the gender column (e.g., "F," "M," and "woman") with "Male" and "Female" to maintain uniformity.

![366966648-b7e64cd3-96b6-4b10-a12e-d0ea61267a1b](https://github.com/user-attachments/assets/129556ec-55b4-4575-b32f-a5cfea74a5a2)

3. Ensuring Data Integrity: I checked all numerical columns (like Purchase Price, Sale Price, Profit, etc.) for correct formats and missing values. All values were found to be properly formatted.



## Data Transformation

After cleaning the dataset, I applied two major transformations:

1. Date to Month Conversion: I extracted the month from the "Date" column using the Excel TEXT function, creating a new "Month" column for monthly analysis.

![366966630-f7befd67-e520-4d00-8609-a3d31280025e](https://github.com/user-attachments/assets/48170aa8-85f4-4312-b4a4-b89ff57f5f3e)

2. Age Group Categorization: I used IFS and AND functions to categorize customers into three age groups:
   - Seniors: Age ≥ 60
   - Middle-aged: Age between 30 and 60
   - Younger: Age < 30

![366966637-4055b318-46e3-460e-93e0-d1aee699399d](https://github.com/user-attachments/assets/7a064ce5-c841-43fe-aa4d-5321db8be342)

## Data Analysis

With the cleaned and transformed dataset, I proceeded with data analysis using PivotTables. The following sections outline the steps taken to answer each business question.

### Top Three Products by Revenue

I created a PivotTable to display the top three products by revenue. A PivotChart (bar chart) was added to visualize this data.
Top Products: 
1. Laptop
2. Jeans
3. Tv

![366978894-5a287818-a30b-4e82-844a-05373fe16c94](https://github.com/user-attachments/assets/533fd37f-8546-4e51-b796-f2644eb0c721)

### Average Delivery Time by Product

To calculate the average delivery time for each product, I created another PivotTable, adjusting the value field settings to display the average rather than the sum.

![366966601-29f0ccc5-880b-4e37-950e-0d18765a7ecc](https://github.com/user-attachments/assets/57e70c36-2ef5-492f-aa9a-b4862803641b)

### Total Revenue by Month

I analyzed revenue trends by month by utilizing the transformed "Month" column. A line chart was used to display this trend, showing monthly revenue fluctuations.

![366966679-6cd8d889-fdfe-4541-95f8-f1cf839a6ad1](https://github.com/user-attachments/assets/c6e88fbe-2894-42e6-a984-cb88199b20d2)

###  Top Five States by Quantity of Items Purchased

I created a PivotTable to rank states based on the quantity of items purchased. The top five states were visualized using a bar chart.

![366966668-533d023d-6b25-4f0f-a65d-9ce2260dd96b](https://github.com/user-attachments/assets/b21a947c-cd5f-4fe8-bfac-4e7441b7565b)

### Age Group with Most Purchases

I grouped customers by age and calculated the total revenue generated by each group. The results were visualized using a pie chart.
- Age Group with Most Purchases: Middle-aged (30-60 years)

![366966565-57cb39c9-536d-4a0b-89b5-43231685d08b](https://github.com/user-attachments/assets/6e026398-eeaa-496e-bb06-04eed954e498)


## Visualization

###  Dashboard Design

After addressing the business questions through thorough data analysis, I moved on to designing a fully interactive and user-friendly dashboard. This dashboard is designed to provide a visual representation of the insights derived from the data, making it easier for stakeholders to interpret and act upon the findings.

The dashboard consists of the following key visualizations:

1. Top Three Products by Revenue: A bar chart that highlights the top-performing products based on total revenue.
2. Average Delivery Time: A bar chart that displays the average delivery time (in days) for each product.
3. Revenue by Month: A line chart that illustrates the revenue trends across each month.
4. Top Five States by Quantity of Items Purchased: A bar chart that ranks the top five states in terms of the number of items purchased.
5. Age Group Purchases: A pie chart that breaks down the sales based on customer age groups.

### Dashboard Interactivity

To enhance the dashboard's functionality, I incorporated several slicers:

- Product Category
- Salesperson
- Gender
- State

These slicers enable users to interact with the dashboard in a meaningful way, giving them the ability to explore various perspectives on the sales data.

![366966609-2235be8e-8005-49a6-9598-4d16aea7d995](https://github.com/user-attachments/assets/fff15e26-cf0f-466e-a8ed-6d7683ed0d74)

## Analysis and Insights

Based on the data analysis and visualizations, the following key insights were derived:

1. Top-Selling Products: The highest revenue-generating products are laptops, jeans, and watches.
2. Dominance of Middle-Aged Buyers: The middle-aged demographic (30-60 years) emerged as the most active customer group in terms of purchases.
3. Regional Sales Hotspots: The top-performing states by quantity of items purchased are Atlanta, Houston, and Washington D.C.

## Recommendations

1. Focus marketing campaigns on the top-selling products (laptops, jeans, and watches) to capitalize on their popularity.
2. Tailor marketing strategies to appeal specifically to the middle-aged demographic (30-60 years).
3. Implement targeted promotional activities in the top-performing states (Atlanta, Houston, and Washington D.C.) to further strengthen market presence.

## Conclusion

This project highlights the importance of data cleaning, transformation, and visualization in deriving actionable insights. The interactive dashboard offers a clear, dynamic way to monitor sales performance and customer trends, helping businesses like Kinetix Ventures make data-driven decisions to improve sales and customer targeting. The insights gained from this analysis provide a solid foundation for strategic decision-making and future growth initiatives.
