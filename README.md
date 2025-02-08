# **Walmart Sales Forecasting: Data Visualization and Analysis using R**

## **Project Description**
- This project focuses on Walmart Sales Forecasting, aiming to predict future sales with data visualization and exploratory data analysis (EDA) using R. The insights derived from the dataset will help in better inventory management, revenue calculation, and understanding sales dynamics. Visualizations are used to identify patterns, trends, and relationships in the sales data, providing valuable insights into Walmart's retail performance across various stores and departments.

## **Objectives**
- Accurate Sales Prediction: The primary objective is to predict sales accurately to optimize inventory levels and enhance revenue calculation processes.
- Data Exploration: Perform Exploratory Data Analysis (EDA) to discover trends, patterns, and relationships between sales and other influencing factors such as temperature, CPI, store type, and more.
- Insight Generation: Uncover insights into customer behavior and sales trends to assist Walmart in decision-making and business planning.
  
## **Scope of Project**
- Sales Forecasting: Predicting future sales based on historical data.
- Data Analysis: Analyzing relationships between sales and external factors like CPI, temperature, and holidays.
- Visualization: Creating interactive and insightful visualizations to understand sales patterns, store performance, and department-wise sales.
- Exploratory Data Analysis (EDA): Investigating the dataset to find hidden insights and trends that may influence sales forecasting.

## **Environment Setup & Dependencies**
- You can install the required packages by running:
```bash
install.packages(c("ggplot2", "dplyr", "tidyr", "lubridate", "readr"))
```

## **Reproducibility Guide**
- To reproduce the analysis and visualizations:
- Clone the repository.
- Place the raw dataset files (like features2.csv, stores.csv, etc.) in the data/ folder.
- Run the R script (Walmart_sales_forecasting.Rmd or another relevant R file) in RStudio or your preferred R environment.
- The visualizations will be generated and saved in the visuals/ folder.

## **Results & Findings**
- Sales Patterns: Store 20 has the highest sales, and store type A records the highest sales among the store types.
- Sales during Holidays: Sales are significantly higher during holidays compared to normal days.
- Seasonal Trends: Sales peak in November, notably during Black Friday and Thanksgiving.
- Department Sales: Department 92 in Store A has the highest sales, showcasing significant variation in performance across departments.
- Store Type and Sales: Store Type A has the largest sales volume, while Store Type C has the lowest.
  
## **Conclusion**
- The analysis and visualizations highlight key insights into Walmart's sales performance, with particular focus on:
- Store performance, with Store 20 leading in sales.
- The importance of holidays and seasonal trends in driving higher sales.
- The effectiveness of different store types and departments in driving revenue.
- These insights provide stakeholders with the necessary information to optimize inventory management, plan for peak sales periods, and make strategic decisions based on historical sales data.

## **References**
- Walmart Sales Dataset(https://www.kaggle.com/datasets/aslanahmedov/walmart-sales-forecast)
