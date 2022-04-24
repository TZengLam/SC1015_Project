# SC1015_Project_DSF1

## About
This is a SC1015 Mini Project which focuses on the relationship between car brand and price. There are many factors that can affect the price of car but one interesting factor is the brand of the car. It was important to determine if customers are spending money on the brand itself or acquiring the specifications of the car. From a car manufacturing brand perspective, it also shows how they value their uniqueness in comparison to other brands.

## Contributors
Ong Jun An- Data cleaning, EDA, Machine Learning, Presentation

Tham Zeng Lam- Problem formulation, EDA, Data Analysis, Presentation

## Problem Definition
1) How can we predict the price of a car?
2) How does brand play a part in affecting car prices?

## Data Set
Webscraped from: https://www.sgcarmart.com/main/index.php
## File Description
.pptx - Powerpoint slides for presentation

CleaningDataSet.ipynb - Cleaning Raw Dataset [Dataset](../main/Cleaning%20Data/CleaningDataSet.ipynb)

Assignment.ipynb - Main Notebook 

Data Description.txt - Column Data Description

(Error Free) sgcarmart.csv - Raw dataset

Clean sgcarmart dataset as of 24MAR2022.csv - Cleaned dataset

## Models Used
1) Linear Regression
2) Random Forest


## Conclusion

### a) How can we predict the price of a car?

We can predict the price of a car by using a regression model with the help of random forest that determines the few most important variables affecting the price.

### b) How does brand play a part in affecting car prices?

From the diverging bars obtained, we can conclude that brand does play a part in affecting car prices to a large extent. Well-known luxury brands like Ferrari, Lotus, Rolls Royce deviate from the typical price by a large positive extent. On the other hand, a brand like British sportscar manufacturer Aston Martin might be less popular in our Singapore society, resulting in Aston Marton pricing their cars less than expected. An interesting insight derived from this analysis is that a sportscar brand like Aston Marton does not necessarily mean the car is overpriced for its given specifications as we need to take into account important factors like its deregistration value and power.

For cars that do not deivate much from the price of a typical car like Honda and Kia, we can also conclude that these brands priced their cars independently of their brand.

## Learnings from this project
-Web scrapping Techniques

-Cross Validation Techniques

-Random Forest model

-Diverging bar for visualisation

-One Hot encoding

-ANOVA statistical test with categorical variables

## References
-Web Scrapping Tool
https://webscraper.io/

-Linear Regression Module
https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LinearRegression.html

-Random Forest Regression Module
https://scikitlearn.org/stable/modules/generated/sklearn.ensemble.RandomForestRegressor.html#sklearn.ensemble.RandomForestRegressor

-Information on Linear Regression
https://www.scribbr.com/statistics/multiple-linear-regression/

-Information on Random Forest Regression
https://www.section.io/engineering-education/introduction-to-random-forest-in-machine-learning/ 

-Information on One-Way ANOVA Test
https://www.scribbr.com/statistics/one-way-anova/

-Slide Template Used
https://slidesgo.com/theme/driving-center#search-car&position-4&results-18
