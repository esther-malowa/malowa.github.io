#  Data Portfolio 

This is my portfolio website

😄

💻

## Insights into Restaurant Customer Satisfaction Analysis

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

  



  





