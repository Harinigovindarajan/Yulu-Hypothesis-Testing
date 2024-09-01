# Yulu Bikes Demand Analysis

## Overview

This project aims to analyze the factors affecting the demand for shared electric cycles in the Indian market, specifically those provided by Yulu Bikes. Yulu is a leading micro-mobility service provider in India, offering a sustainable commuting solution through shared electric cycles. The analysis focuses on identifying the significant variables that predict demand and understanding how well these variables describe the overall demand for Yulu's services.

## Dataset Description

The dataset includes data related to the usage of Yulu's electric cycles, captured across different times and conditions. The features in the dataset are as follows:

- **datetime**: Date and time of the record.
- **season**: Season of the year (1: Spring, 2: Summer, 3: Fall, 4: Winter).
- **holiday**: Whether the day is a holiday (1) or not (0).
- **workingday**: Whether the day is a working day (1) or not (0).
- **weather**: Weather condition (1: Clear, 2: Mist/Cloudy, 3: Light Snow/Rain, 4: Heavy Rain/Snow).
- **temp**: Actual temperature in Celsius.
- **atemp**: Feels-like temperature in Celsius.
- **humidity**: Humidity percentage.
- **windspeed**: Wind speed.
- **casual**: Count of casual users.
- **registered**: Count of registered users.
- **count**: Total count of rented bikes (casual + registered).

## Project Objectives

1. **Exploratory Data Analysis (EDA)**:
   - Explore the dataset to understand its structure, characteristics, and any potential issues like missing values or outliers.
   - Conduct univariate and bivariate analyses to identify relationships between key variables.

2. **Hypothesis Testing**:
   - Perform a 2-sample t-test to determine if the working day has an effect on the number of electric cycles rented.
   - Use ANOVA to test if the number of cycles rented differs across different seasons and weather conditions.
   - Conduct a Chi-square test to examine if weather is dependent on the season.

3. **Insights and Recommendations**:
   - Provide actionable insights based on the analysis to help Yulu Bikes optimize their operations and marketing strategies.

## Analysis Approach

1. **Data Exploration**:
   - Import the dataset and perform an initial exploration, including checking the structure, data types, missing values, and basic statistics.
   - Convert categorical variables to appropriate data types.
   - Visualize the data using distribution plots, bar plots, and count plots to understand the distribution of continuous and categorical variables.

2. **Bivariate Analysis**:
   - Analyze the relationships between variables such as working day vs. count, season vs. count, and weather vs. count using scatter plots, box plots, and correlation analysis.

3. **Hypothesis Testing**:
   - **2-Sample T-Test**: Test the hypothesis that the number of electric cycles rented is different on working days compared to non-working days.
   - **ANOVA**: Test if the number of cycles rented varies significantly across different seasons and weather conditions.
   - **Chi-Square Test**: Examine the dependency between weather conditions and seasons.

4. **Statistical Assumptions**:
   - Check the normality and equal variance assumptions using visual methods (histograms, Q-Q plots) and statistical tests (Levene’s test, Shapiro-Wilk test).

5. **Decision Making**:
   - Based on the p-values from the hypothesis tests, determine whether to accept or reject the null hypotheses.
   - Interpret the results to provide meaningful business insights.

6. **Recommendations**:
   - Provide recommendations based on the analysis to help Yulu Bikes make data-driven decisions regarding operations and marketing.


😇 Please do check the code and let me know if any changes required to make it better. 🤞🤞

⚡⚡ Thank you in advance for visiting and reviewing the code. 🙌😎
