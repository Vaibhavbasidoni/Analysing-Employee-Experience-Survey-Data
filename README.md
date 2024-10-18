# Analysing Employee Experience Survey Data

## Project Overview
This project conducts an in-depth analysis of employee experience survey data from a fictional organization. The goal is to uncover insights into job satisfaction, work-life balance, and overall engagement across various employee demographics and departments.

## Data Analysis Process

1. Data Preparation
   - Loaded the survey data from a CSV file into a pandas DataFrame
   - Converted Likert scale responses (e.g., 'Strongly Disagree' to 'Strongly Agree') to numeric values for analysis

2. Descriptive Statistics
   - Calculated summary statistics (mean, median, mode, standard deviation) for Overall Engagement and Job Satisfaction
   - Analyzed the distribution of responses for key survey questions

3. Demographic Analysis
   - Examined job satisfaction levels across different age brackets
   - Compared work-life balance and compensation satisfaction between genders
   - Analyzed engagement levels across various ethnic groups

4. Departmental Analysis
   - Calculated average job satisfaction for each department
   - Identified departments with the highest and lowest satisfaction levels

5. Correlation Analysis
   - Investigated the relationship between Work-Life Balance and Overall Engagement
   - Explored correlations between different aspects of employee experience (e.g., Management Support and Job Satisfaction)

6. Hypothesis Testing
   - Conducted t-tests to compare job satisfaction between the two largest departments
   - Tested for significant differences in engagement levels across age groups

7. Data Visualization
   - Created bar charts to display job satisfaction by department and age bracket
   - Generated a correlation heatmap to visualize relationships between different survey factors
   - Produced scatter plots to illustrate the relationship between work-life balance and overall engagement

## Key Findings

1. Age-related Trends: The 18-24 age group showed the highest average job satisfaction (3.43), while the 35-44 age group had the lowest (2.0). However, the 25-34 age group reported the best work-life balance (4.67).

2. Departmental Differences: Design department reported the highest job satisfaction (5.0), while IT reported the lowest (1.0). However, these results should be interpreted cautiously due to small sample sizes in some departments.

3. Work-Life Balance Impact: Surprisingly, there was a moderate negative correlation (-0.3610) between Work-Life Balance and Overall Engagement. However, this correlation was not statistically significant (p-value = 0.1861).

4. Demographic Patterns: Female employees reported slightly higher compensation satisfaction (2.89) compared to male employees (2.50). In terms of ethnicity, Caucasian employees reported the highest work-life balance (4.67), while Hispanic employees reported the lowest (1.0).

5. Correlation Insights: The correlation heatmap revealed strong positive correlations between several factors, such as Job Satisfaction and Overall Engagement, suggesting that these aspects of employee experience are closely interrelated.

6. Statistical Comparison: When comparing job satisfaction between the Sales and Product Development departments (the two largest departments), no statistically significant difference was found (t-statistic = 0.0795, p-value = 0.9397).

These findings provide valuable insights into the employee experience across different demographics and departments, highlighting areas of strength and potential improvement in the organization.

This project demonstrates the application of data analysis techniques to gain actionable insights from employee survey data, potentially informing HR strategies and management decisions to improve employee satisfaction and engagement.
