# Upliance-AI-assignment
# Data Cleaning and Preparing Data for Analysis

### Data Preparation
First, I merged all the sheets of the provided workbook using pandas and performed join operations. I then dropped the duplicate columns to ensure that only unique columns remain in my dataset.

### Feature Engineering
I added two new columns to enhance the dataset:
1. **Session Duration Status**: This column indicates whether the cooking session is more than or less than 30 minutes.
2. **Age Group**: This column displays whether the customer is above or below 30 years of age.

### Data Analysis
Utilizing the groupby and sort_values functions in Python, I derived insightful relations:
1. **Total Orders per Location and Meal Type**: Analyzed the distribution of orders across different locations and meal types.
2. **Total Orders per Age and Food Dish**: Examined the correlation between customer age groups and their preferred food dishes.

### Visualization with Pivot Tables
To visualize the findings, I used pivot tables and created the following charts:
1. **Column and Bar Charts**: These visualizations depict customer ratings per dish and the amount spent per dish, respectively.
2. **Pie Chart**: This chart visualizes the preferred meal type (dinner, lunch, breakfast) based on the total orders made and the amount of money spent.
3. **Customer Demographics Analysis**: Analyzed how demographics such as 'Location' and 'Age group' play a crucial role in understanding user behaviors.
4. **Revenue Spread Analysis**: Attempted to explain the spread of revenue throughout a day, across the specified age groups.

By cleaning and preparing the data, and performing in-depth analysis and visualization, this project provides valuable insights into customer behaviors and preferences, enabling data-driven decision-making.
