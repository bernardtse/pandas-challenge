# pandas-challenge
PyCitySchools

## Contents
1. [Overview](#1-overview)
2. [Repository](#2-repository)
3. [Deployment](#3-deployment)
4. [Data Analysis](#4-data-analysis)
5. [References](#5-references)

## 1. Overview  
In this challenge, the analysis of school and standardised test data for a city’s school district was performed. The goal was to extract key metrics about student performance, school spending, school size, and type. Using Pandas and Jupyter Notebook, various calculations and aggregations were made to generate insights, trends, and performance summaries for different schools within the district. Patterns such as the impact of school size and spending on student performance were revealed, providing valuable information for strategic decisions regarding future school budgets and priorities. The project involved creating multiple dataframes to showcase performance across several dimensions, including district-wide averages, school-specific summaries, and performance rankings.


## 2. Repository  
The repository contains the following files:

- **Jupyter Notebook**
  - [`PyCitySchools/PyCitySchools.ipynb`](PyCitySchools/PyCitySchools.ipynb): The main notebook containing the analysis and calculations.
  
- **Report**
  - [`PyCitySchools/report.md`](PyCitySchools/report.md): A written report summarising the analysis and drawing conclusions from the data.
  
- **Raw Data**
  - `PyCitySchools/Resources/schools_complete.csv`: The dataset containing information on schools.
  - `PyCitySchools/Resources/students_complete.csv`: The dataset containing student performance data.

## 3. Deployment  
To run this analysis on your local machine, ensure the following Python libraries are installed:

- `pandas`
- `pathlib`

Once the libraries are installed, simply clone this repository, navigate to the folder containing the Jupyter Notebook, and open it in Jupyter to run the analysis. The results will be displayed within the notebook.


## 4. Data Analysis  
This analysis answers the following questions:

1. **District Summary:**
   - Total number of schools, total students, total budget, and average test scores for math and reading.
   - Percentage of students passing math, reading, and both subjects (overall passing).

2. **School Summary:**
   - Summary of each school’s performance, including average math and reading scores, percentage of students passing math and reading, and overall passing rates.
   - Information on school budgets and per-student spending.

3. **Highest and Lowest Performing Schools:**
   - Schools sorted by overall passing percentage, highlighting the best and worst-performing institutions.

4. **Math and Reading Scores by Grade:**
   - Breakdown of average math and reading scores by grade level (9th to 12th) for each school.

5. **Scores by School Spending:**
   - Analysis of school performance based on per-student spending, showing how spending levels correlate with academic performance.

6. **Scores by School Size:**
   - Comparison of school performance based on school size (small, medium, and large schools).

7. **Scores by School Type:**
   - Performance breakdown based on the type of school (Charter or District).


Key observations:
- Schools with higher spending generally show higher overall passing percentages, but there is also a noticeable trend where smaller schools tend to perform better in terms of overall passing rates.
- Larger schools tend to have more varied performance results, which could be due to differences in resources and student populations.


## 5. References  
Data generated by Mockaroo, LLC (2022). Realistic Data Generator. Data for this dataset was generated by edX Boot Camps LLC, and is intended for educational purposes only. [https://mockaroo.com/](https://mockaroo.com/)
