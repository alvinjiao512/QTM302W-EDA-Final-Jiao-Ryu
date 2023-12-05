# Data Science Salary Analysis

## Introduction

This repository contains an exploratory data analysis (EDA) notebook that aims to investigate potential salary disparities among data science professionals in the United States. The dataset used encompasses various components, including total yearly compensation, total years of experience, gender, and 24 other variables related to data science employees. The primary objective is to determine if there is a salary disparity among different regions defined by the US Census Bureau, and if so, to identify potential causes.

## Structure

The analysis is structured as follows:

1. **Data Exploration:**
   - Loading necessary packages and reading the dataset.
   - Providing an overview of the dataset, including key variables such as total yearly compensation, race, education level, years of experience, and geographic location.

2. **Data Cleaning:**
   - Standardizing variable names to snake_case for consistency.
   - Cleaning up the location variable to focus on US locations and categorizing them into four regions: Northeast, Midwest, South, and West.

3. **Exploratory Data Analysis:**
   - Investigating the relationship between total yearly compensation and location using visualizations, including a boxplot and density plot.
   - Examining the association between years of experience and total compensation, considering gender as a factor.
   - Exploring the relationship between years of experience and location to identify potential confounders.

4. **Conclusion & Implications:**
   - Summarizing key findings and addressing limitations in the dataset, such as missing education data.
   - Outlining future steps to modify hypotheses, address missing data, and conduct a more in-depth analysis.

5. **Cost of Living Exploration:**
   - Exploring the cost of living index by region to provide additional context for salary disparities.

6. **Salary vs. Majors vs. Gender Exploration:**
   - Analyzing the relationship between undergraduate majors, mid-career median salaries, and gender using bar plots.

## Usage

To replicate the analysis, you can follow the steps outlined in the provided R Markdown notebook (`EDA_Notebook.Rmd`). Make sure to have the required packages installed.

Feel free to explore and contribute to this analysis to enhance our understanding of salary dynamics within the data science industry.

## References

- Original dataset source: [Kaggle - Data Science and Tech Salaries Visualization](https://www.kaggle.com/code/febiec/data-science-and-tech-salaries-visualization/notebook)
