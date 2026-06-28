# README

## 1. Business Problem Summary
Identify the key drivers of monthly retail store sales and provide evidence-based recommendations for management.

## 2. Dataset Description
The dataset contains 320 store-month observations across multiple regions and store formats, including operational, marketing, and customer metrics.

## 3. Dependent and Independent Variables
- Dependent variable: Monthly Sales
- Independent variables: Footfall, Staff Count, Marketing Spend, Average Discount %, Inventory Availability %, Competitor Distance, Customer Rating, Holiday Flag, Region dummies, Store Type dummies.

## 4. Regression Approach
Simple linear regression models were estimated first, followed by a multiple linear regression model.

## 5. Dummy Variable Approach
Categorical variables were encoded using dummy variables:
- Region reference category: West
- Store type reference category: Residential

## 6. Model Comparison Summary
The multiple regression model achieved superior performance:
- R²: 85.7% vs 73.6%
- RMSE: $39,196 vs $53,207
- MAE: $30,893 vs $42,435

## 7. Final Model Selected
Multiple linear regression model.

## 8. Business Recommendation
Focus on increasing footfall, optimizing staffing, improving inventory availability, and investing in effective marketing channels.

## 9. Assumptions and Limitations
The analysis assumes linearity, independence, homoscedasticity, and reliable measurements. Regression results indicate association rather than causation.

## 10. Screenshots Included
Screenshots should include:
- Regression output tables
- Model comparison summary
- Residual analysis outputs
- Final recommendation summary
