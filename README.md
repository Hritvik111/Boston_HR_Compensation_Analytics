# Boston_HR_Compensation_Analytics

## Overview
This project focuses on analyzing and improving operational efficiencies within the City of Boston's workforce. Utilizing a dataset of employee salaries and other relevant details, the project aims to identify trends, correlations, and opportunities for operational improvement.

## Table of Contents
- [Overview](#overview)
- [Dataset Description](#dataset-description)
- [Technologies Used](#technologies-used)
- [Installation Instructions](#installation-instructions)
- [Usage](#usage)
- [Visualizations](#visualizations)
- [Key Findings](#key-findings)
- [Conclusion](#conclusion)
- [Contributions](#contributions)
  
## Dataset Description
The dataset contains detailed employee salary information from the City of Boston, including the following fields:
- **_id**: Unique identifier for the employee.
- **NAME**: The name of the employee.
- **DEPARTMENT_NAME**: The department where the employee works.
- **TITLE**: The job title held by the employee.
- **REGULAR**: The base salary paid to the employee.
- **RETRO**: Retroactive payments made to the employee.
- **OTHER**: Additional compensation outside of regular and overtime pay.
- **OVERTIME**: The additional salary earned from overtime.
- **INJURED**: Payments related to work-related injuries.
- **DETAIL**: Earnings related to specific assignments or details.
- **QUINN_EDUCATION**: Compensation related to the Quinn Bill educational incentive.
- **TOTAL GROSS**: The total salary earned by the employee, including regular, overtime, and other payments.
- **POSTAL**: The employee's postal code.

This dataset is used to analyze salary distributions, departmental averages, overtime patterns, and other factors to identify potential operational improvements.

## Technologies Used
- **Python**: For data cleaning and analysis.
- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical operations.
- **Matplotlib & Seaborn**: For data visualization.
- **Tableau**: For interactive dashboards (external visualization tool).
- **Jupyter Notebook**: For documenting the analysis workflow.

## Usage
Open each Jupyter Notebook (.ipynb) in a Jupyter environment to execute the code.
Follow the notebooks in sequence:
- 01-Data-Cleaning.ipynb: Load and clean the dataset.
- 02-EDA.ipynb: Perform exploratory data analysis and generate visualizations.
- 03-Data-Ingestion.ipynb: Load cleaned data and ingest into database.

## Visualizations
In addition to the static visualizations created with Matplotlib and Seaborn, an interactive dashboard has been created using Tableau Public. This dashboard allows users to explore the data dynamically, filter by department, and visualize salary trends across different categories. The Tableau Public visualization can be accessed here -  [City of Boston HR Dashboard](https://public.tableau.com/app/profile/hritvik.mahajan/viz/CityofBostonHRDashboard-2023/Dashboard2).

![image](https://github.com/user-attachments/assets/66cc698e-a4ed-42b3-96c1-ce516422077a)

These visualizations can also be found in the visuals/ folder.

## Key Findings

### 1. Overtime Costs and Employee Compensation
- The **Boston Police Department** incurred the highest overtime costs in the last fiscal year, followed closely by the **Boston Fire Department**.
- The **Boston Fire Department** leads in average total gross pay at **$155,369.50**, highlighting disparities across departmental pay structures.

### 2. Retroactive Pay Distribution
- The **Special Education Department** had the highest retroactive pay, totaling **$2,961,040.98** for 847 employees. 
- **Facilities Management** follows with **$2,721,415.78** distributed among 604 employees, indicating significant retroactive payments.

### 3. Overtime Workforce Dependence
- **90.28%** of employees in the **Boston Fire Department** and **81.55%** in the **Boston Police Department** work overtime, suggesting a reliance on overtime that may affect operational sustainability.

### 4. Dependence on Non-Regular Compensation
- Departments like **Mission Hill K-8** and **Business Services** report over **40-50%** of gross pay from non-regular sources, while elementary schools average **8-10%**. This inconsistency highlights potential areas for payroll policy revision.

### 5. Additional Compensation Insights
- The **Boston Police Department**, **Boston Fire Department**, and **Transportation** departments show a high number of employees receiving additional compensation. This suggests opportunities for centralizing customer support strategies to optimize resource allocation.

### 6. Quinn Education Benefits Impact
- Employees with **Quinn Education** benefits receive an average total compensation of **$172,410**, compared to **$77,519** for those without. This indicates the potential value of expanding educational benefits to improve employee retention.

### 7. Regional Payroll Disparities
- The highest average regular pay is found in postal code **2065**, with **$223,456.69**. Addressing regional disparities can aid the **Department of Innovation and Technology (DoIT)** in effective resource allocation.

## Conclusion
The insights gathered reflect significant areas for operational improvement within the City of Boston’s workforce policies. By leveraging these findings, we can enhance efficiency, equity, and employee satisfaction across departments.

## Contributions
Contributions are welcome! Please open an issue or submit a pull request if you would like to contribute to this project.

## Installation Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/Hritvik111/Boston_HR_Compensation_Analytics.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Boston_HR_Compensation_Analytics
   ```
3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```
