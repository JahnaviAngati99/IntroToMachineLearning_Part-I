# Machine Learning Assignment Analysis - Boston Housing Dataset

## Project Overview
This project is an in-depth analysis of the Boston Housing dataset as part of a Machine Learning assignment. It explores relationships between various housing attributes and the impact on crime rates, accessibility to radial highways, tax rates, and pupil-teacher ratios by town.

## Dataset Description
The Boston Housing dataset comprises 506 rows and 13 columns. Each row represents a suburb of Boston, and the columns represent different variables such as:
- `crim`: Per capita crime rate by town
- `zn`: Proportion of residential land zoned for lots over 25,000 sq.ft.
- `indus`: Proportion of non-retail business acres per town
- ... and so on for all 13 attributes.

## Analysis Findings
- Crime rates (`crim`) demonstrate a negative linear relationship with the distance to employment centres (`dis`) and a positive relationship with the proportion of older structures (`age`).
- Lower status of the population (`lstat`) is negatively correlated with the median value of homes (`medv`).
- A deep dive into high crime rates, tax rates, and pupil-teacher ratios offers insightful distributions and potential areas for municipal improvement.

## Technical Approach
- Descriptive statistics and visualization tools were utilized to uncover the underlying patterns within the data.
- Linear regression models were applied to determine the relationships between variables.
- Histograms and scatter plots were created to visualize the distributions and correlations.
