# BCGx - Data Science Virtual Internship Program

This repository contains the tasks and projects I have completed as part of the Data Science Virtual Internship Program offered by Boston Consulting Group (BCG) through Forage. This program was divided into 4 tasks, each of which was designed to give me a taste of the kind of work that BCG's data scientists do on a daily basis. The tasks were as follows:

1. **Task 1: Business Understanding & Hypothesis Framing**
2. **Task 2: Exploratory Data Analysis**
3. **Task 3: Feature Engineering & Modeling**
4. **Task 4: Findings & Recommendations**

## Table of Contents

- [BCGx - Data Science Virtual Internship Program](#bcgx---data-science-virtual-internship-program)
  - [Table of Contents](#table-of-contents)
  - [Task 1: Business Understanding \& Hypothesis Framing](#task-1-business-understanding--hypothesis-framing)
  - [Task 2: Exploratory Data Analysis](#task-2-exploratory-data-analysis)
    - [Data Overview](#data-overview)
    - [Key Findings](#key-findings)
      - [1. Churn and Customer Characteristics](#1-churn-and-customer-characteristics)
      - [2. Sales Channels and Churn](#2-sales-channels-and-churn)
      - [3. Pricing Trends and Churn Impact](#3-pricing-trends-and-churn-impact)
      - [4. Integrated Customer and Price Analysis](#4-integrated-customer-and-price-analysis)
    - [Conclusions \& Recommendations](#conclusions--recommendations)
    - [Next Steps](#next-steps)
  - [Task 3: Feature Engineering \& Modeling](#task-3-feature-engineering--modeling)
  - [Task 4: Findings \& Recommendations](#task-4-findings--recommendations)

## Task 1: Business Understanding & Hypothesis Framing

In this task, I focused on understanding the business problem faced by PowerCo, a major gas and electricity utility. I identified the key business objectives and framed hypotheses that could explain the customer churn issue. I also determined the necessary data required for analysis and outlined the techniques to be used for investigating the problem. Finally, I drafted an email to the Associate Director summarizing my approach and the initial steps to be taken.

## Task 2: Exploratory Data Analysis

In this task, we performed an in-depth exploratory data analysis (EDA) on the provided datasets to understand customer churn and its correlation with various attributes. The analysis included data quality checks, visualization of numerical and categorical variables, and the relationship between churn and different features.

### Data Overview

- **client_data.csv**: Contains 14,606 customer records with 26 features, including energy consumption, customer details, and churn status.
- **price_data.csv**: Contains 193,002 records related to energy pricing trends over time.
- **Merged Dataset**: The datasets were merged using the `id` field, allowing for a comprehensive analysis of customer behavior and pricing trends.
- **Target Variable**: `churn` (whether a customer churns within the next 3 months).

### Key Findings

#### 1. Churn and Customer Characteristics

- **Electricity Consumption (`cons_12m`)**: Churned customers generally have lower consumption.
- **Net Margin (`net_margin`)**: Customers with lower net margins are more likely to churn.
- **Customer Tenure (`num_years_antig`)**: Longer tenure reduces churn likelihood.
- **Subscription Power (`pow_max`)**: Higher power subscriptions correspond to lower churn rates.

#### 2. Sales Channels and Churn

- Certain sales channels have higher churn rates, particularly the "MISSING" category.
- Customers acquired through specific campaigns (`origin_up`) show varying churn behaviors.

#### 3. Pricing Trends and Churn Impact

- **Off-Peak Prices (`price_off_peak_var`)**: Higher off-peak prices correlate with higher churn.
- **Peak and Mid-Peak Prices**: No significant effect on churn.
- Energy price fluctuations over time show seasonal effects but require further study for causality.

#### 4. Integrated Customer and Price Analysis

- Higher off-peak prices contribute to increased churn.
- Low-margin customers are more sensitive to price increases and more likely to churn.
- Customers with lower electricity consumption churn at a higher rate.
- Sales channels significantly impact customer loyalty, with certain channels exhibiting higher churn rates.

### Conclusions & Recommendations

- **Focus on Retention Strategies**: Target low-consumption customers with incentives to stay.
- **Review Off-Peak Pricing Strategy**: High off-peak pricing may be a churn driver.
- **Improve Customer Acquisition**: Sales channels with high churn rates should be reassessed.
- **Strengthen Loyalty Programs**: Long-term customers are less likely to churn, indicating loyalty programs could be beneficial.
- **Segment Customers Based on Risk**: Develop specific retention plans for customers with high churn probability.

### Next Steps

- Further segmentation analysis to identify high-risk customer groups.
- Predictive modeling to forecast churn probability using machine learning.
- A/B testing on pricing strategies to evaluate their impact on churn reduction.

This EDA provides key insights into customer behavior, pricing dynamics, and churn factors, forming the basis for deeper predictive analytics and strategic decision-making.

## Task 3: Feature Engineering & Modeling

## Task 4: Findings & Recommendations

