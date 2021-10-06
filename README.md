# ds_salary_project
Repo for the data science salary prediction from Glassdoor project

## Code and Resources 
###### Python Version: 3.7
###### Packages: pandas, numpy, matplotlib, seaborn, selenium, flask, json, pickle 
###### Data : https://github.com/PlayingNumbers/ds_salary_proj 


## Data Cleaning
After collect the data, I needed to clean the data so that it was usable for our model. I made the following changes and created the following variables:
- Parsed numeric data out of salary
- Made columns for employer provided salary and hourly wages
- Removed rows without salary
- Parsed rating out of company text
- Made a new column for company state
- Added a column for if the job was at the company’s headquarters
- Transformed founded date into age of company
- Made columns for if different skills were listed in the job description:
  - Python
  - R
  - Excel
  - AWS
  - Spark
- Column for simplified job title and Seniority
- Column for description length
