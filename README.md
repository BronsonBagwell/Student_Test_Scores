# Student Test Scores EDA
Exploratory data analysis of student performance patterns in high school exams.

## Overview
This project explores a Kaggle dataset of US high school student exam scores to uncover patterns in academic performance. The analysis examines how demographic and socioeconomic factors relate to math, reading, and writing scores through visualizations and summary statistics.

## Dataset
- **Source:** [Students Performance in Exams](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams) via Kaggle
- **Size:** 1,000 students, 8 variables
- **Key variables:** Gender, race/ethnicity, parental education level, lunch type, test preparation course, math score, reading score, writing score

## Methods
- Created a total score feature combining math, reading, and writing scores
- Distribution analysis and box plots across demographic groups
- Correlation analysis between scores and categorical variables
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
2. Open the R Markdown or HTML file in RStudio
3. Or [view on Kaggle](https://www.kaggle.com/code/bronsonb/student-test-scores-eda)
