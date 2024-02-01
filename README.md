**Automotive Price Prediction**

**Overview**
This project focuses on predicting automotive prices through comprehensive data analysis and model building. The dataset provides insights into various factors influencing car prices, including brand preferences, fuel types, car types, symbolling, engine characteristics, and more. The linear regression model developed exhibits a high level of explanatory power, with an R-squared value of 90.8%.

**Data Analysis**

**Price Distribution**
Right-skewed distribution: Majority of prices below 15,000.
Significant difference between mean and median: Indicates skewness.
High variance: 85% of prices below 18,500.

**Brand Preferences**
Toyota favored: Preferred car company.

**Fuel Type and Car Type**
Gas-fuelled cars outnumber diesel.
Sedan most preferred: Dominant car type.

**Symbolling and Pricing**
0 and 1 values most common: Widespread symbolling.
-1 symbolling associated with higher prices.
Symbolling 3 and -2 have similar price ranges with a dip at 1.

**Engine Characteristics**
ohc engine type favored.
ohcv has the highest price range.
Jaguar and Buick have the highest average prices.

**Fuel Systems and Drive Wheels**
mpfi and 2bbl common fuel systems.
Significant differences in drive wheel preferences.
RWD drive wheels costlier.

**Correlation Analysis**
Positive correlation with price: Curb weight, engine size, horsepower, car width, high-end.
Negative correlation: Citympg, highwaympg, fuel economy.

**Feature Selection**
RFE (Recursive Feature Elimination): 15 columns selected.
Column Removal: Based on high p-values and VIF.

**Model Evaluation**
**Error Term Distribution**
Histogram shows normal distribution: Meets linear regression assumptions.

**Model Performance**
R-squared: 90.8%
Adjusted R-squared: 90.4%
F-statistic: 269.6, highly significant (p-value: 4.79e-69).

**Predictor Significance**
All predictors ("horsepower," "car width," "hatchback," "four," "High-end") have low p-values: Significance indicators.

**Coefficient Interpretation**
Example: Coefficient for "horsepower" is 0.3648, suggesting a 0.3648-unit price increase per one-unit horsepower increase, holding other variables constant.

**Model Comparison**

AIC: -362.7
BIC: -344.9
Indicating a good balance between model fit and complexity.

**Conclusion**
The linear regression model effectively explains approximately 90.8% of the variance in car prices. Key features such as horsepower, car width, hatchback type, four cylinders, and high-end features significantly contribute to predicting car prices. The model demonstrates statistical significance and achieves a well-balanced trade-off between complexity and fit.




