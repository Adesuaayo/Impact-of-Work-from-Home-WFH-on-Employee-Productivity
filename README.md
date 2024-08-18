# Impact of Work-from-Home (WFH) on Employee Productivity

## Overview
This project explores the impact of the transition to Work-from-Home (WFH) on employee productivity. The study involves generating synthetic data, performing data cleaning, and conducting hypothesis testing to assess changes in productivity levels before and after WFH, as well as differences in productivity between male and female employees.

## Table of Contents
1. [Introduction](#introduction)
2. [Dataset](#dataset)
3. [Analysis Process](#analysis-process)
4. [Hypotheses](#hypotheses)
5. [Results](#results)
6. [Conclusion](#conclusion)
7. [How to Run the Code](#how-to-run-the-code)
8. [Technologies Used](#technologies-used)
9. [License](#license)

## Introduction
With the rise of remote work, especially during the COVID-19 pandemic, many organizations have adopted WFH policies. This project aims to analyze how this shift has impacted employee productivity, focusing on two key aspects:
- The overall change in productivity before and after WFH.
- The difference in productivity between male and female employees in the WFH setup.

## Dataset
The dataset is synthetic and was generated to simulate real-world scenarios. It contains 1,000 rows with the following columns:
- `Employee_ID`: A unique identifier for each employee.
- `Age`: Age of the employee (19-60 years).
- `Gender`: Gender of the employee (60% female).
- `Department`: Department where the employee works.
- `Pre_WFH_Productivity`: Productivity score before WFH (scaled 0-100).
- `Post_WFH_Productivity`: Productivity score after WFH (scaled 0-100).

## Analysis Process
### 1. Data Cleaning
- Checked for missing values and inconsistencies.
- Ensured proper data types for each column.

### 2. Normality Tests
- Conducted Shapiro-Wilk tests to check if the productivity scores were normally distributed.

### 3. Hypothesis Testing
- Used the Wilcoxon Signed-Rank Test to compare productivity before and after WFH.
- Applied the Independent T-Test and Mann-Whitney U Test to compare productivity between male and female employees.

## Hypotheses
### Hypothesis 1
- **H0**: There is no significant difference in employee productivity before and after transitioning to WFH.
- **H1**: There is a significant difference in employee productivity before and after transitioning to WFH.

### Hypothesis 2
- **H0**: There is no significant difference in post-WFH productivity between male and female employees.
- **H1**: There is a significant difference in post-WFH productivity between male and female employees.

## Results
- **Hypothesis 1:** The Wilcoxon Signed-Rank Test indicated a significant increase in productivity after WFH.
- **Hypothesis 2:** The Mann-Whitney U Test revealed no significant difference in post-WFH productivity between male and female employees.

## Conclusion
The analysis suggests that transitioning to WFH has positively impacted overall productivity. However, gender does not appear to be a significant factor in determining productivity levels in a WFH setup.

## How to Run the Code
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/WFH-Employee-Productivity-Analysis.git
