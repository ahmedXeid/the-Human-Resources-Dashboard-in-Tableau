# Human Resources Dashboard in Tableau

## Overview
This Tableau dashboard provides insights into employee demographics, department distribution, performance ratings, salary distribution, and tenure. It's an interactive tool designed for HR managers to make data-driven decisions regarding workforce management.

## Features
- **Employee Demographics**: View gender distribution, age groups, and education levels.
- **Department Analysis**: Understand the distribution of employees across departments.
- **Performance Metrics**: Compare employee performance across different education levels.
- **Salary Insights**: Analyze salary distribution by gender, department, and age group.
- **Geographic Distribution**: Visualize employee locations on a map.

## Technologies Used

This project was developed using the following tools and technologies:

- ![Excel](https://img.shields.io/badge/Microsoft%20Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white): For data preparation and analysis.
- ![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white): For data visualization and dashboard creation.

## Data Preparation
- **Dataset**: `HumanResources.csv`
- **Fields**: Includes personal details (name, gender, age), job information (department, title, hire date), education, salary, and location.
- **Data Cleaning**:
  - Calculated age from birthdate.
  - Created a "Full Name" field by concatenating first and last names.
  - Classified employees as "Hired" or "Terminated" based on termination date.

## Visualizations
1. **Overview Dashboard**:
   - **Employee Status Over Time**: Line and area charts for active vs. terminated employees.
   - **Department Breakdown**: Bar chart showing employee count by department.
   - **Demographics**: Pie chart for gender distribution, and stacked bar for education level by age group.
   - **Education and Performance**: Bar chart with trend line showing performance ratings by education level.
   - **Income Distribution**: Comparison of salary across gender and education levels, and average salary per department by age group.
   - **Geographic Location**: Map showing employee distribution across states.

2. **Detailed Employee List Dashboard**:
   - Comprehensive list of employees with demographic, job role, and salary details.
   - Interactive filters to drill down by location, department, or hire date.

## Interactive Features
- **Global Filters**: Apply filters across the dashboard (gender, location, employment status).
- **Clickable Visualizations**: Interactive segments in charts to filter related data across the dashboard.
- **Hover Details**: Tooltips for detailed information on data points.

## Screenshots
Here are some screenshots of the dashboard:

### Overview Dashboard
![Overview Dashboard](images/HR1.png)

### Employee List Dashboard
![Employee List Dashboard](images/HR2.png)

## Getting Started
1. **Download the Tableau Workbook**:
   - Download the `.twbx` file to explore the dashboard in Tableau.
2. **Dataset**:
   - Use the provided `HumanResources.csv` dataset if available, or replace it with similar data.
3. **Customizing Filters**:
   - Modify global filters to focus on specific demographics, locations, or performance metrics.

## Challenges and Solutions
- **Age Calculation**: Used the DATEDIFF function in Tableau to dynamically calculate employee age.
- **Performance Ratings as Text**: Assigned a numerical scale to text ratings to enable trend analysis.
- **Combined Name Field**: Concatenated First Name and Last Name fields for easier reference in the dashboard.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Conclusion
The Human Resources Dashboard in Tableau provides a comprehensive view of workforce metrics, enabling HR teams to make informed, data-driven decisions. With interactive filters and visualizations, it offers flexibility to explore various HR insights efficiently.
