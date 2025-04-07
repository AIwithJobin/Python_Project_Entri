# Python_Project_Entri

# Employee Data Analysis Project

## Overview
This project analyzes employee data from ABC Company to provide insights into team distribution, position segregation, age groups, salary expenditure, and correlations between age and salary. The dataset consists of 458 rows and 9 columns, covering various attributes of employees across different teams.

## Dataset Description
The dataset includes the following columns:
- **Name**: Employee's name
- **Team**: Team the employee belongs to
- **Number**: Employee's jersey number
- **Position**: Employee's position within the company
- **Age**: Employee's age
- **Height**: Employee's height (corrected during preprocessing)
- **Weight**: Employee's weight
- **College**: Employee's college/university
- **Salary**: Employee's annual salary

## Preprocessing
The "Height" column in the original dataset contained invalid date strings. These values were replaced with random integers between 150 and 180 to ensure data consistency and integrity.

## Analysis Tasks

### 1. Distribution of Employees Across Teams
- **Method**: Calculated the count and percentage of employees in each team.
- **Key Insight**: The majority of employees are concentrated in specific teams such as the Boston Celtics, Brooklyn Nets, and New York Knicks.

### 2. Segregation of Employees by Position
- **Method**: Calculated the count of employees in each position.
- **Key Insight**: Junior positions (PG, SG) dominate the dataset, indicating a higher number of entry-level employees.

### 3. Predominant Age Group
- **Method**: Analyzed the age distribution to identify the most common age group.
- **Key Insight**: The predominant age group is between 25 and 30 years, suggesting a relatively young workforce.

### 4. Highest Salary Expenditure
- **Method**: Grouped data by team and position to calculate total salary expenditure.
- **Key Insight**: The highest salary expenditure is in the "PG" position within the "Brooklyn Nets" team.

### 5. Correlation Between Age and Salary
- **Method**: Calculated the correlation coefficient and visualized the relationship using a scatter plot.
- **Key Insight**: A moderate positive correlation exists between age and salary, indicating that older employees tend to earn higher salaries.

## Visualizations

### 1. Team Distribution
- **Type**: Bar chart
- **Description**: Shows the number of employees in each team.

### 2. Position Distribution
- **Type**: Bar chart
- **Description**: Shows the number of employees in each position.

### 3. Age Distribution
- **Type**: Histogram
- **Description**: Displays the distribution of employees by age.

### 4. Salary Distribution by Team
- **Type**: Box plot
- **Description**: Illustrates the salary distribution across different teams.

### 5. Age vs Salary Correlation
- **Type**: Scatter plot
- **Description**: Visualizes the relationship between age and salary.

## Data Story
The analysis reveals several key trends:
- **Team Concentration**: Specific teams have a significantly higher number of employees, indicating potential resource allocation strategies.
- **Position Dominance**: Junior positions are more prevalent, suggesting opportunities for career advancement and training.
- **Age Demographics**: The workforce is predominantly young, which may influence company culture and benefits planning.
- **Salary Expenditure**: Higher expenditure in specific roles highlights areas of strategic investment.
- **Age-Salary Relationship**: The positive correlation between age and salary aligns with typical career progression patterns.

## Project Structure
