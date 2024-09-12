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


<p align="center">
  <img src="ibb.co/dLpJ3Mp" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <em>Figure 1: Data Loaded in PowerQuery</em>
</p>

To begin, a reorganization of the columns was undertaken, enhancing the data's structure and readability. As part of this process, the "Policy Number" column was designated as the index for efficient referencing. Additionally, an extraneous column at the end of the dataset was removed to streamline the data's presentation. Moreover, a new column called "Age Group" was introduced, facilitating subsequent analysis based on age-related criteria.

Subsequently, efforts were made to improve data interpretability through the application of functions such as replace() and proper(). For instance, the values "Husband" and "Wife" within the "Insured Relationship" column were unified and transformed into a more generic category, "Married". These transformations aimed to enhance the visualisation of the data and simplify the subsequent analytical processes.

<p align="center">
  <img src="https://raw.githubusercontent.com/blackcrowX/blackcrowX.github.io/main/images/project_I/screenshot_2.jpg"/>
  <em>Figure 2: Data in Excel After Transformation</em>
</p>

The final step in the data preparation phase involved a thorough examination for missing values, duplicates, or inconsistencies within the dataset. In this particular project, the data proved to be free from such issues, bolstering the overall data quality and ensuring a robust analysis. The assessment was performed using the countif() function, mitigating the potential risks of errors and biases that could arise from incomplete or inconsistent data entries. This meticulous verification process lays the foundation for accurate and reliable analysis in subsequent stages.


## Visualisation

The data visualisation stage of the Excel project involved transforming the analyzed information into meaningful and easily understandable visual representations. This allowed for a comprehensive overview of the modeled data on a dedicated dashboard, enhancing the viewer's ability to gain insights efficiently. Several key steps were taken to achieve this goal.

To begin, a new Excel sheet was created specifically for the purpose of visualizing the data. This dedicated sheet served as the canvas for assembling various charts, tables, and visual elements, consolidating all the modeled information in a single, easily accessible location. This approach ensured that viewers could review the data at a glance, enabling a holistic understanding of the analysis outcomes.

To enhance interactivity and provide viewers with more control over the data exploration process, slicers were incorporated into the dashboard. Slicers function as interactive filters that allow for further data segmentation based on different criteria and the specific interests of the viewer. By utilizing slicers, viewers can dynamically adjust the displayed data, focusing on specific subsets or dimensions of the analysis that are most relevant to their investigation.

<p align="center">
  <img src="https://raw.githubusercontent.com/blackcrowX/blackcrowX.github.io/main/images/project_I/screenshot_7.jpg"/>
  <em>Figure 7: Car Insurance Claim Fraud Dashboard Visualisation</em>
</p>

These features collectively contribute to a more intuitive and user-friendly data visualisation experience. By presenting the analyzed information on a dedicated dashboard, viewers can quickly grasp the key insights and trends without feeling overwhelmed by the complexity of the underlying data. The inclusion of slicers adds an extra layer of interactivity, enabling viewers to explore the data from different angles and refine their analysis based on specific filters of interest.

Through this data visualisation process, the Excel project successfully addresses the initial research question regarding car insurance claim fraud. The consolidated dashboard and interactive slicers empower viewers to effortlessly navigate through the modeled data, facilitating a comprehensive understanding of the analysis outcomes while ensuring a streamlined and engaging data exploration experience.

## Analysis

Using the modelled data in the dashboard, I was able to answer the initial questions and provide insights on car insurance claim fraud as following:

- **State:** The state of Ohio stands out as having the highest occurrence of fraudulent claims. Although the difference between the fraudulent and non-fraudulent datasets is relatively minor (36.6% versus 34.5%), it is worth monitoring claims originating from policies in Ohio for potential irregularities.

- **Insured:** The analysis reveals that individuals in the age range of 35-44, particularly those who are single, constitute the largest group involved in fraudulent activities. Notably, males and individuals with a doctor's degree exhibit a higher propensity for fraudulent claims. Surprisingly, individuals with interests in chess or cross fit, along with men in executive managerial positions and women in sales occupations, show significantly higher claim rates in the fraudulent dataset compared to the non-fraudulent dataset. These observations suggest the need for increased scrutiny when assessing claims from insured individuals with these characteristics.

- **Incident:** The analysis highlights that a considerable number of fraudulent incidents occur during midday, primarily involving single-vehicle collisions resulting in substantial damages. Major damages account for a significantly higher percentage (69%) in the fraudulent dataset compared to the non-fraudulent dataset (14%). Additionally, incidents involving parked cars or vehicle theft are relatively rare in cases of car insurance claim fraud. These insights can aid in the identification of potentially fraudulent claims.

- **Correlation:** Through regression analysis, it was determined that there is no statistically significant correlation between the duration of policyholders' tenure (months as a customer) and the occurrence of fraudulent claims. However, it is worth noting that the analysis suggests a lower predicted frequency of fraudulent claims with longer customer tenure. This finding may be influenced by the limited number of policies spanning the observed time period, and caution should be exercised when interpreting this relationship based on the available data.

These data analysis findings provide valuable insights into the characteristics and patterns associated with car insurance claim fraud. The identified trends and relationships offer actionable recommendations for heightened vigilance when handling claims from specific states, insured individuals with certain profiles, and incidents displaying particular patterns. The analysis contributes to a better understanding of fraudulent claims and supports decision-making processes aimed at detecting and mitigating insurance fraud.

## Conclusion

In conclusion, this project successfully analyzed car insurance claim fraud using Microsoft Excel, leveraging advanced techniques such as PowerQuery, PowerPivot, PivotTable, PivotChart, and Regression Analysis. By investigating key indicators and patterns associated with fraudulent claims, insurance companies can enhance their fraud detection and prevention strategies.

Moving forward, several areas warrant further exploration:

1. **Develop advanced predictive models:** Utilize machine learning algorithms and techniques to build predictive models that can accurately detect fraudulent claims in real-time.

2. **Expand the dataset:** Incorporate a larger and more diverse dataset to increase the robustness and generalizability of the analysis.

By pursuing these next steps, insurance companies can further strengthen their ability to identify and mitigate car insurance claim fraud, ultimately minimizing financial losses and improving customer trust.
