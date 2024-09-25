# Boston_HR_Compensation_Analytics

## Overview
This project focuses on analyzing and improving operational efficiencies within the City of Boston's workforce. Utilizing a dataset of employee salaries and other relevant details, the project aims to identify trends, correlations, and opportunities for operational improvement.

## Table of Contents
- [Dataset Description](#dataset-description)
- [Project Structure](#project-structure)
- [Technologies Used](#technologies-used)
- [Installation Instructions](#installation-instructions)
- [Usage](#usage)
- [Visualizations](#visualizations)
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
In addition to the static visualizations created with Matplotlib and Seaborn, an interactive dashboard has been created using Tableau Public. This dashboard allows users to explore the data dynamically, filter by department or job title, and visualize salary trends across different categories. The Tableau Public visualization can be accessed here -  [City of Boston HR Dashboard](https://public.tableau.com/app/profile/hritvik.mahajan/viz/CityofBostonHRDashboard-2023/Dashboard2).

These visualizations can also be found in the visuals/ folder.


## Conclusion and Findings

Through the analysis of the City of Boston's employee salary dataset, several key findings and insights emerged:

1. 

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
