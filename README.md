# Executive Summary / README

## Project Overview
This project aims to analyze employee attrition at Frito Lay for DDSAnalytics, an analytics company specializing in talent management solutions. The goal is to identify key factors associated with employee turnover and build a predictive model for attrition. The analysis is designed to help Frito Lay proactively manage and retain talent.

## Data & Methodology
- **Data Source:** The primary dataset, provided as `CaseStudy1-data.csv`, contains employee records with various attributes such as Monthly Income, Job Role, OverTime status, Age, and more.
- **Analysis Approach:** 
  - We conducted exploratory data analysis (EDA) using visualization and statistical tests (e.g., t-tests) to identify variables that significantly differ between employees who left and those who stayed.
  - The top factors were selected based on statistical significance and visual evidence.
  - A K-Nearest Neighbors (KNN) model and a Naive Bayes model were built and evaluated. Model performance was measured in terms of sensitivity, specificity, and overall accuracy.
- **Tools:** All analysis and modeling were performed in R using packages such as **tidyverse**, **ggplot2**, **caret**, and **e1071**.

## Key Findings
- **Significant Factors:** Our analysis identified several key factors significantly related to attrition. Among the top three were:
  - **OverTime:** Employees working overtime were significantly more likely to leave.
  - **Monthly Income:** Variations in monthly income showed a strong relationship with attrition rates.
  - **Job Role:** Specific job roles were found to have different attrition patterns, suggesting that role-specific issues may be at play.

## Model Performance
- **Predictive Models:** Both the KNN and Naive Bayes models were developed to predict attrition.
- **Evaluation Metrics:** The final models were evaluated based on sensitivity and specificity. Both models achieved at least 60% on both metrics on the training and validation sets.
- **Competition Set Validation:** The KNN predictive model was applied to the unlabeled Competition Set. Predictions were saved in a CSV file (ordered by ID) for further validation.

## Repository Contents
  - RMarkdown file with the complete analysis and code.
  - Presentation slides.
  - Final prediction CSV file (`CaseStudy1PredictionsStreeter Attrition.csv`).


## Conclusion
This study provides actionable insights into the factors driving employee attrition at Frito Lay. By focusing on key issues such as overtime and income disparities, Frito Lay can implement targeted strategies to improve retention. 

