![image](https://github.com/PhamTrungHieu2001/Data-Professions/assets/73734497/6d028156-ed8e-4376-a58d-a5fa94a9e359)![image](https://github.com/PhamTrungHieu2001/Data-Professions/assets/73734497/b3986b50-c147-4bdc-a909-5191d010755a)![image](https://github.com/PhamTrungHieu2001/Data-Professions/assets/73734497/9fd36859-8cc6-43c3-9d13-2c30f2c2fbde)# Data-Professions
# Introduction
## Overview

## Objective
The project focuses on answering questions like:

## Tool used
Power Query: data cleaning
PowerBI: data visualization

## Data cleaning
1. Group other professions into 1 group
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

2. Calculate the average salary
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
1. Total participants and average age
2. Average salary by country
3. Average salary by job title
4. Favorite programming languages
5. Number of participants by level of education
6. Happiness with salary and coworkers 
