# Student Test Scores EDA
Exploratory data analysis of student performance patterns in exams.

## Overview
This project explores the Kaggle "Students Performance in Exams" dataset of exam scores for 1,000 students to uncover patterns in academic performance. The analysis examines how demographic and socioeconomic factors relate to math, reading, and writing scores through visualizations and summary statistics.

## Dataset
- **Source:** [Students Performance in Exams](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams) via Kaggle
- **Size:** 1,000 students, 8 variables
- **Key variables:** Gender, race/ethnicity, parental education level, lunch type, test preparation course, math score, reading score, writing score

## Methods
- Created a total score feature as the average of the math, reading, and writing scores
- Assigned a letter grade from the total score: F for 0 to 59, D for above 59 to 69, C for above 69 to 79, B for above 79 to 89, and A for above 89 to 100
- Distribution analysis and box plots across demographic groups
- Correlation analysis between scores and categorical variables, and among the three scores
- Visualizations of performance gaps by gender, parental education, and test prep completion

## Key Findings
- Students who completed test preparation courses scored consistently higher across all subjects
- Parental education level showed a positive relationship with student performance
- Reading and writing scores were highly correlated; math showed more independent variation

## Tools & Libraries
![R](https://img.shields.io/badge/R-276DC3?style=flat-square&logo=R&logoColor=white)
![tidyverse](https://img.shields.io/badge/tidyverse-1A162D?style=flat-square&logo=r&logoColor=white)
![ggplot2](https://img.shields.io/badge/ggplot2-276DC3?style=flat-square&logo=r&logoColor=white)

## How to Run
1. Clone the repository: `git clone https://github.com/BronsonBagwell/Student_Test_Scores.git`
2. Install the required R packages: `install.packages(c("tidyverse", "knitr"))` (`grid` ships with R)
3. Open `student-test-scores-eda.ipynb` in Jupyter with an R kernel; the included `StudentsPerformance.csv` is read from the repo root
4. Or [view on Kaggle](https://www.kaggle.com/code/bronsonb/student-test-scores-eda)
