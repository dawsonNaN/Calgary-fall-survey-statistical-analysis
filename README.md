# Project Overview———Calgary-fall-survey-statistical-analysis
This project examines public perceptions of safety and quality of life in Calgary using the 2024 and 2025 Fall Survey of Calgarians.

The objective is to apply statistical inference methods to investigate changes in residents' perceptions over time and explore relationships between demographic characteristics and quality-of-life assessments.

Two statistical analyses were conducted using R, focusing on hypothesis testing, confidence intervals, data visualization, and interpretation of statistical results.

# Dataset

Source: City of Calgary — Fall Survey of Calgarians (2024 and 2025)

Population: Calgary residents aged 18 and older

Sample size: 2,500 completed interviews per year

Sampling approach: Random telephone sampling

Survey variables: Perceived safety, perceived change in quality of life, and demographic characteristics

Data sources:

Fall Survey of Calgarians 2024

Fall Survey of Calgarians 2025

# Research Questions and Statistical Methods

Analysis 1: Changes in Perceived Safety (2024 vs. 2025)

Research Question:

Is there a statistically significant difference in the proportion of Calgary residents who perceive the city as safe between 2024 and 2025?

Method: Two-Sample Proportion Test

A two-sample proportion test was used to compare the proportions of respondents who considered Calgary safe across two independent survey years.

Results:

2024: 73.39% perceived Calgary as safe.

2025: 73.96% perceived Calgary as safe.

Observed difference: 0.57 percentage points.

P-value: 0.6477

95% Confidence Interval for the proportion difference: (-0.0187, 0.03015)

Since the p-value exceeds 0.05, we failed to reject the null hypothesis.

Conclusion: There was insufficient statistical evidence to suggest that the proportion of Calgary residents perceiving the city as safe differed between 2024 and 2025.

Analysis 2: Age Group and Perceived Change in Quality of Life

Research Question:

Is there an association between age group and perceived change in Calgary's quality of life?

Method: Chi-Square Test of Independence

A chi-square test of independence was conducted to examine the relationship between two categorical variables:

Age Group: 18–24, 25–34, 35–44, 45–54, 55–64, and 65+

Perceived Change in Quality of Life: Improved, Stayed the Same, or Worsened

Contingency tables and proportional bar charts were used to summarize differences in responses across age groups.

Results:

Significance level: α = 0.05

P-value: approximately 0.0000154

Since the p-value is significantly below 0.05, the null hypothesis of independence was rejected.

Conclusion: The distribution of perceived changes in quality of life differs across age groups. This provides evidence of a statistical association but does not establish causation.
