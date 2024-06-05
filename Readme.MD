# Linear Regression for Bike Demand Prediction

## General Information
- Background: This project aims to build a multiple linear regression model to predict the demand for shared bikes in the American market. The bike-sharing provider, BoomBikes, is facing revenue challenges due to the ongoing COVID-19 pandemic and wants to understand the factors affecting bike demand to optimize its business strategy.
- Business Problem: BoomBikes wants to understand the demand for shared bikes after the quarantine situation ends and the economy restores to a healthy state. The company wants to identify significant variables affecting bike demand and how well these variables describe the demand dynamics.
- Dataset: The dataset being used is the Bike Sharing dataset, which contains information about daily bike demands across the American market based on various factors such as weather conditions, temperature, humidity, and other relevant variables.

## Conclusions
- Conclusion 1: The multiple linear regression model achieved an R-squared score of 0.452 on the test set, indicating that it explains approximately 45.2% of the variance in bike demand.
- Conclusion 2: The variables 'temp', 'hum', and 'windspeed' were found to be significant predictors of bike demand.
- Conclusion 3: The demand for shared bikes is positively correlated with temperature and negatively correlated with humidity and windspeed.
- Conclusion 4: The 'yr' column, indicating the year of bike demand data (2018 or 2019), was found to be a valuable predictor of bike demand, contrary to initial assumptions.

## Technologies Used
- pandas - version 1.3.3
- scikit-learn - version 0.24.2
- matplotlib - version 3.4.3

## Acknowledgements
- This project was inspired by the need to address the revenue challenges faced by BoomBikes during the COVID-19 pandemic.
- References: ({http://dx.doi.org/10.1007/s13748-013-0040-3)

## Contact
Created by [@bfarhana] - feel free to contact me!
