# 🔗 [View the Report Analysis](Placement_analysis.ipynb)


# 📊 Student Placement Data Analysis

This project analyzes student placement data to explore factors influencing placement success and salary levels. By examining this data, we aim to uncover trends and insights that can help educational institutions and students optimize placement strategies. The potential for actionable insights on how educational background, grades, and work experience impact employment outcomes makes this an exciting area of analysis.

## 📑 Table of Contents
- [📋 Dataset Information](#-dataset-information)
- [🔍 Problems](#-problems)
- [🧹 Data Cleaning](#-data-cleaning)
- [📈 Analysis](#-analysis)
- [📊 Dashboard Takeaways](#-dashboard-takeaways)
- [📜 Conclusion](#-conclusion)

## 📋 Dataset Information

The data used in this analysis comes from `Placement_Data_Full_Class.csv`. Here’s a brief overview of each column in the dataset:

- **sl_no**: Serial number (identifier).
- **gender**: Gender of the student (Male or Female).
- **ssc_p**: Secondary Education percentage (10th Grade).
- **ssc_b**: Board of Education (Central or Others) for 10th Grade.
- **hsc_p**: Higher Secondary Education percentage (12th Grade).
- **hsc_b**: Board of Education (Central or Others) for 12th Grade.
- **hsc_s**: Specialization in Higher Secondary Education (Commerce, Science, Arts).
- **degree_p**: Degree percentage.
- **degree_t**: Type of degree (Science & Tech, Comm&Mgmt, Others).
- **workex**: Work experience (Yes or No).
- **etest_p**: Employability test percentage.
- **specialisation**: MBA Specialization (Mkt&HR or Mkt&Fin).
- **mba_p**: MBA percentage.
- **status**: Placement status (Placed or Not Placed).
- **salary**: Salary offered (NaN if not placed).

Credit goes to the original data provider for this comprehensive dataset, which enables us to examine key predictors of placement success.

## 🔍 Problems

This analysis seeks to answer the following primary questions:

1. **What factors significantly impact a student’s placement status?**
2. **Which variables are strongly associated with higher salaries?**
3. **How do educational backgrounds influence placement outcomes?**

## 🧹 Data Cleaning

To ensure data integrity, the following data cleaning steps were undertaken:

- **Handled Missing Values**: Filled missing values in the salary column for students not placed.
- **Standardized Categorical Values**: Ensured consistency in fields such as `workex` and `status`.
- **Removed Duplicate Records**: Avoided redundancy by eliminating duplicate entries.

Included in the analysis notebook are images showing data inconsistencies and transformations applied to correct them, highlighting the data cleaning process.

## 📈 Analysis

For a focused analysis, only rows with complete data for critical placement and salary prediction fields were included (e.g., excluding rows with missing salary data when placement status was "Not Placed").

## 📊 Dashboard Takeaways

Each visualization in the dashboard represents a key insight:

- **Gender vs. Placement Rate**: Shows how placement success varies by gender.
- **Degree Type vs. Salary**: Highlights differences in salary by degree type.
- **Work Experience Impact**: Illustrates how prior work experience affects both placement chances and salary.

Each visualization addresses a specific question, demonstrating patterns that can inform actionable recommendations for students or educational institutions.

## 📜 Conclusion

Based on the analysis, the following conclusions were drawn:

- **Placement Predictors**: Academic performance and prior work experience significantly impact placement chances.
- **Salary Influences**: Degree type and employability test scores correlate with higher salaries.
- **Actionable Recommendations**: Students with work experience and strong academic performance, particularly in certain degree types, are more likely to achieve placement and command higher salaries. Institutions might consider integrating more practical work experiences into their programs.

