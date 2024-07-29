#  Data Portfolio 

This is my portfolio website
😄

## Insights into Restaurant Customer Satisfaction Analysis

## Table Of Contents
. [Project Overview](#project-overview)

. [Data Sources](#data-sources)

. [Tools](#tools)

. [Data Cleaning/Preparation](#data-cleaning/preparation)

. [Exploratory Data Analysis(EDA)](#exploratory-data-analysis(EDA))

. [Data Analysis](#data-analysis)

. [Results/Findings](#results/findings)

. [Recommendations](#recommendations)

. [Limitations](#limitations)





### Project Overview

This project aims to analyze and understand the factors that influence customer satisfaction in the restaurant industry. By leveraging a dataset containing various attributes related to customer experiences, the goal is to identify key trends, patterns, and insights to help restaurant managers and owners improve their services and enhance customer satisfaction.

### Data Sources

Restaurant dataset: The primary dataset used  for this analysis is the "Restaurant dataset.csv" 

### Tools
- Excel - Data Cleaning [Download here](https://microsoft.com)
- MySQL - Data Analysis [Download here](https://microsoft.com) 
- PowerBI - Creating reports  [Download here](https://microsoft.com)

### Data Cleaning/Preparation
In the initial data preparation phase, I performed the following tasks;

1. Data loading and inspection

2. Handling missing values

3. Data cleaning and formatting

### Exploratory Data Analysis(EDA)

EDA involved exploring restaurant sales to answer key questions such as;

- 	What are the Popular Dishes and Services?

- 	Analyze Dining Patterns

### Data Analysis
 
 ```SQL
select CustomerID,
 Age,
 Gender,
 Income,
 VisitFrequency,
 round(AverageSpend, 0),
 PreferredCuisine,
 TimeOfVisit,
 GroupSize,
 DiningOccasion,
 MealType,
 LoyaltyProgramMember,
 round(WaitTime,0),
 ServiceRating,
 FoodRating,
 AmbianceRating
from restaurant_customer_satisfaction;
```

### Results/Findings
1. Service rating is higher than food and ambiance rating.
2. Italian cuisine generates more income than other preferred cuisine.
3. The sum of loyalty program members is only seven hundred and twenty.

### Recommendations
1. Train kitchen staff on maintaining consistency.
2. Create a comfortable and visually appealing environment.
3. Introduce new and unique Italian dishes regularly.
4. Offer seasonal specials and promotions focusing on Italian cuisine.
5. Run targeted advertising campaigns featuring popular Italian dishes.
6. Offer incentives for joining, such as a free appetizer or dessert upon sign-up.
7. Train staff to inform and encourage customers to join the loyalty program.
8. Celebrate member anniversaries or birthdays with special offers or discounts.

### Limitations
I had to remove all decimals in the AverageSpend and WaitTime columns because they would affect the accuracy of my conclusions from the analysis.



  



  





