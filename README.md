# Data-Professions
For more interactions with the dashboard, please download [Data Profession.pbix](https://github.com/PhamTrungHieu2001/Data-Professions/blob/main/Data%20Profession.pbix)

## Overview
This project uses PowerBI to analyze survey data about various data professions. The survey includes responses from roles such as Data Analyst, Data Engineer, Data Scientist, and others.
The goal is to create interactive dashboards and reports to visualize the survey results. These insights will help understand the distribution of roles and trends in the data industry.

## Tool used
- Power Query: data cleaning
- PowerBI: data visualization

## Data cleaning
### 1. Group other professions into 1 group
- Select 'Split Column by Delimiter' -> 'Custom' -> '('
- Delete the split column

| **Before**                                | **After**                                                                                   |
|---------------------------------------------|--------------------------------------------------------------------------------------------------|
| Other (Please Specify):Analytics Consultant  | Other |
| Other (Please Specify):FP&A Analyst | Other |
| Other (Please Specify):BI Developer  | Other |
| Other (Please Specify):Manager, Business Intelligence Develop | Other |
| Other (Please Specify):Business Analyst  | Other |

- The same method applies to the 'Industry', 'Programming Language', and 'Country' columns

### 2. Calculate the average salary
- Split 'Q3 - Current Yearly Salary (in USD)' into 2 columns by '-'
- Calculate the average of those 2 columns

| **Before**                                | **After**                                                                                   |
|---------------------------------------------|--------------------------------------------------------------------------------------------------|
| 106k-125k | 115500 |
| 41k-65k | 53000 |
| 0-40k | 20000 |
| 150k-225k | 187500 |
| 41k-65k | 53000 |

## Data analysis
### 1. Total participants and average age
- There are 630 survey participants and their average age is about 30.

![1](https://github.com/PhamTrungHieu2001/Data-Professions/blob/main/images/age.jpg)

### 2. Average salary by country
The USA has the highest average salary, at nearly $80,000 a year.

![2](https://github.com/PhamTrungHieu2001/Data-Professions/blob/main/images/country.jpg)

### 3. Average salary by job title
Data Scientist is the highest-paying job compared to all other data professions.

![3](https://github.com/PhamTrungHieu2001/Data-Professions/blob/main/images/job.jpg)

### 4. Favorite programming languages
The most favorite programming language among people working in data is Python.

![4](https://github.com/PhamTrungHieu2001/Data-Professions/blob/main/images/gender.jpg)

### 5. Number of participants by level of education
The majority of survey participants have a bachelor's degree.

![5](https://github.com/PhamTrungHieu2001/Data-Professions/blob/main/images/education.jpg)

### 6. Happiness with salary and coworkers 
People are not too happy with their salary and coworkers.

![6](https://github.com/PhamTrungHieu2001/Data-Professions/blob/main/images/happiness.jpg)

