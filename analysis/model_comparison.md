# Model Comparison: Simple vs Multiple Regression

| Required Item | Simple Regression (Footfall) | Multiple Regression |
|---|---|---|
| Model name | Simple Linear Regression: Monthly Sales ~ Footfall | Multiple Linear Regression: Monthly Sales ~ 14 Predictors |
| Variables used | Dependent: Monthly Sales; Independent: Footfall | Dependent: Monthly Sales; Independent: Footfall, Staff Count, Marketing Spend, Discount %, Inventory Availability, Competitor Distance, Customer Rating, Holiday Flag, Region and Store Type dummies |
| R-squared | 0.7363 | 0.8569 |
| Significant variables | Footfall (p<0.001) | Footfall, Staff Count, Marketing Spend, Inventory Availability, Competitor Distance, Customer Rating, Holiday Flag, Region_East, Region_North, Type_Airport, Type_High Street, Type_Mall |
| Business usefulness | Strong predictor of sales using a single operational metric | Stronger strategic model capturing operational, geographic and store-format effects |
| Limitations | Omits important drivers and explains only 73.6% of variation | More complex; some variables remain insignificant and causality cannot be inferred |

## Comparison Summary
The multiple regression model outperforms the simple regression model across all evaluation metrics. R² improves from 73.6% to 85.7%, while RMSE falls from $53,207 to $39,196 and MAE falls from $42,435 to $30,893.

The most important predictors are footfall, marketing spend, inventory availability and store format. Average discount percentage and South region effects are not statistically significant and should not be over-interpreted.

**Recommended model:** Multiple regression due to its higher explanatory power and stronger business applicability.
