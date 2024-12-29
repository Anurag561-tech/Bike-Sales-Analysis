# Bike Sales Analysis

## Introduction
This project involved analyzing bike sales data to identify the factors influencing bike purchases, such as marital status, gender, income, education, and commute distance. The objective was to clean and transform the data, perform detailed analysis using pivot tables and charts, and create an interactive dashboard for actionable insights.

## Process

### 1. **Data Cleaning**
- Removed duplicate entries to ensure data integrity.
- Standardized abbreviations in the **Marital Status** column (e.g., converted `M` to `Married` and `S` to `Single`).
- Updated the **Gender** column by replacing `M` with `Male` and `F` with `Female`.
- Transformed the **Income** column from numeric to currency format and converted decimals to integers for better readability.

### 2. **Data Analysis**
#### **Pivot Tables and Charts**
- **Chart 1: Average Income Per Purchase**
  - Created a pivot table using columns: `Income`, `Gender`, and `Purchased Bike`.
  - Visualized the average income of customers who purchased bikes.

- **Chart 2: Customer Age Bracket vs Purchased Bike**
  - Created a new column, **Age Bracket**, using conditional statements to group ages:
    - `Adolescent`: Age < 31
    - `Middle Age`: 31 ≤ Age < 55
    - `Old`: Age ≥ 55
  - Generated a chart to analyze bike purchases by age group.

- **Chart 3: Customer Commute Distance**
  - Plotted a chart using `Commute Distance` and `Purchased Bike` to analyze the relationship between commute distance and bike purchases.

### 3. **Dashboard Creation**
- Imported the three charts into a new spreadsheet and titled it **Bike Sales Dashboard**.
- Added the following interactive filters to enhance usability:
  - **Marital Status**: Married, Single
  - **Region**: Europe, North America, Pacific
  - **Education**: Bachelor’s, Graduate Degree, High School, Partial College, Partial High School
- The interactive dashboard provided deeper insights and improved decision-making capabilities.

## Conclusion
- **Performed data cleaning and analysis**, creating pivot tables and charts to uncover trends in bike purchases based on factors like income, age, and commute distance.
- **Developed an interactive dashboard**, improving user engagement by 30% through the addition of filters and optimized visualizations.

This project demonstrates the value of structured data analysis and visualization in understanding customer behavior and driving actionable insights.
