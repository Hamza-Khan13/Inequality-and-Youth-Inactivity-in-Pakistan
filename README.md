# Inactive Youth in Pakistan: Does Inequality of Opportunity Matter?

This repository contains code for the research paper titled "Inactive Youth in Pakistan: Does Inequality of Opportunity Matter?". The data for this study was taken from Labour Force Publications | Pakistan Bureau of Statistics (pbs.gov.pk) for the year 2018-19.

## 1. Data Extraction in R

The folder Data Extraction in R contains the raw data file LFS.xlsx, Main.Rmd R markdown file that extracts only the useful columns using R which tends to be faster than pandas when handling huge datasets. The folder also contains the Questionnaire 2018-19.pdf which contains the questionnaire used for the survey and CODING-LFS 2018-19 that provides a description of columns and how the data is encoded.

## 2. Data Preprocessing and Exploratory Data Analysis in Python

The folder Data Preprocessing and Exploratory Data Analysis in Python contains the file data.xlsx that was created earlier and main.ipynb file that performs preprocessing, exploratory data analysis, and creates the Final_data.xlsx file for Regression Analysis. The main.ipynb file also includes visualization code for data exploration.

## 3. Regression Analysis in R

The folder Regression Analysis in R contains the Final_data.xlsx and Regression_analysis.rmd files. Due to the nature of the study, logistic regression was used and the Regression_analysis.rmd file creates an odds_ratio table for evaluation.
