# Excel Bike Buyers Analysis Dashboard

This project demonstrates the creation of an interactive dashboard in Microsoft Excel to analyze the demographics and purchasing behavior of bike buyers.

## Project Overview

The goal of this project is to take a raw dataset of customer information, clean and prepare it for analysis, and then create a dynamic dashboard that allows users to filter and explore the data to gain insights into what factors influence a customer's decision to purchase a bike.

## Dataset

The dataset used in this project is the "Bike Buyers" dataset, which can be downloaded from [GitHub](https://github.com/AlexTheAnalyst/Excel-Tutorial/blob/main/Excel%20Project%20Dataset.xlsx). It contains demographic and financial information about potential customers, as well as a column indicating whether or not they purchased a bike.

## Project Steps

The project is broken down into the following key steps:

### 1. Data Cleaning and Preparation

- **Removing Duplicates:** The first step in cleaning the data is to remove any duplicate rows to ensure data integrity.
- **Replacing Abbreviations:** The 'Marital Status' and 'Gender' columns were updated to replace single-letter abbreviations ('M', 'S', 'F', 'M') with their full-text equivalents ('Married', 'Single', 'Female', 'Male') for better readability.
- **Creating Age Brackets:** A new column, 'Age Brackets', was created using `IFS` statement to group customers into 'Adolescent', 'Middle Age', and 'Old' categories. This simplifies age-based analysis.
- **Cleaning Commute Distance:** The 'Commute Distance' column was cleaned to ensure proper sorting and visualization.

### 2. Data Visualization

Pivot tables and charts were used to create the following visualizations:

- **Average Income vs. Bike Purchase:** A bar chart comparing the average income of customers who purchased a bike versus those who did not, broken down by gender.
- **Commute Distance vs. Bike Purchase:** A bar chart showing the number of customers who purchased a bike based on their commute distance.
- **Age Bracket vs. Bike Purchase:** A line chart illustrating the relationship between a customer's age bracket and their likelihood of purchasing a bike.

### 3. Interactive Dashboard

An interactive dashboard was created to bring all the visualizations together in one place.

- **Dashboard Layout:** The charts were arranged on a new sheet, and the gridlines were removed for a cleaner look.
- **Slicers:** Slicers were added to the dashboard to allow for dynamic filtering of the data based on:
    - Marital Status
    - Region
    - Education
    These slicers are connected to all the charts on the dashboard, making them fully interactive.

## Tools Used

- **Microsoft Excel:**
    - Formulas (`IFS` statement)
    - Pivot Tables
    - Pivot Charts
    - Slicers

## How to Use the Dashboard

1.  Open the 'Bike_Buyer_Analysis_Dashboard.xlsx' file.
2.  Navigate to the "Dashboard" sheet.
3.  Use the slicers on the left-hand side to filter the data.
4.  The charts will automatically update based on your selections.

## Conclusion

This project serves as a comprehensive, hands-on example of how to perform data analysis and visualization only in Excel.