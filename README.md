# Census Income and Demographic Analysis

## Project Overview

Census Income and Demographic Analysis is a data analytics project using the UCI Adult Dataset (`adult.data`) to analyze demographic, education, employment and income patterns.

The project follows an end-to-end workflow using **Python, Google Colab and Power BI**.

## Objective

To analyze demographic and employment-related factors associated with income levels and identify meaningful patterns across education, age, occupation, gender, race, workclass, working hours and native country.

## Dataset

- **Dataset:** UCI Adult Dataset – `adult.data`
- **Original working dataset:** 32,561 records × 15 columns
- **Cleaned dataset:** 32,537 records × 15 columns
- **Duplicates removed:** 24
- **Target:** Income (`<=50K` / `>50K`)

### Dataset Source

[UCI Adult Dataset](https://archive.ics.uci.edu/dataset/2/adult)

## Tools & Technologies

- Python
- Google Colab
- Pandas
- Matplotlib
- Seaborn
- Power BI

## Project Workflow

**Dataset → Data Cleaning → Exploratory Data Analysis → Feature Creation → Power BI Dashboard → Insights**

## Data Cleaning

The Python analysis included:

- Handling missing categorical values
- Removing 24 duplicate records
- Creating Age Group
- Creating Work Hours Category
- Validating data types and categorical values
- Preparing the cleaned dataset for Power BI

## Exploratory Data Analysis

EDA was performed on:

- Income distribution
- Age
- Education
- Occupation
- Gender
- Race
- Workclass
- Working hours
- Native country
- Relationships between numerical variables

## Power BI Dashboard

The dashboard contains 3 interactive pages:

### Page 1 – Income Overview
Provides an overall view of income distribution across age groups, education levels and occupations.

### Page 2 – Demographic Analysis
Analyzes income patterns across gender, race, workclass and working-hour categories.

### Page 3 – Detailed Analysis
Provides detailed analysis using age groups, gender, education, native country and Key Influencers.

## Key Findings

- Final cleaned dataset contains **32,537 records**.
- **24.09%** of individuals belong to the `>50K` income group.
- Higher education levels generally show stronger representation in the `>50K` income group.
- Professional and managerial occupations show substantial higher-income representation.
- Income patterns vary across age, gender, race, workclass and working hours.

## Project Files

- [Python Analysis Notebook](./Census_Income_and_Demographic_Analysis.ipynb)
- [Cleaned Dataset](./Census_Income_Cleaned.csv)
- [Original Adult Dataset](./adult.data)
- [Power BI Dashboard](./Census_Income_Demographic_Analysis.pbix)
- [Final Project Documentation](./Census_Income_and_Demographic_Analysis_FINAL.docx)

## Google Colab Notebook

[Open Project in Google Colab](https://colab.research.google.com/drive/1oAlrFtZNnHXwnBg0cUHWhQIgOoNFpJX_?usp=sharing)

## Conclusion

This project demonstrates an end-to-end data analytics workflow from data preparation and exploratory analysis in Python to interactive dashboard development and business insights in Power BI.
