# Used Car Price Prediction Analysis & Inventory Tuning Recomendations

[V1.0 Jupyter Notebook Link](https://github.com/sjt80/car_price_prediction/blob/main/driving_price_of_a_car.ipynb)

### Executive Summary

This report is the result of a comprehensive analysis to understand the key features influencing used car prices. Utilizing advanced data science, including, data cleaning, feature engineering, Multiple Linear Regression models, our goal was to identify attributes that significantly impact the value of used cars. This information is intended to assist dealers to optimize their inventory selection to maximize profitability.

### Dataset Overview

The analysis was conducted with a dataset of almost 500k vehicles accross the United States and included common attributes of used cars, such as year, make, model, mileage, fuel type, transmission type and more. Prior to modeling, the data underwent cleaning to remove or impute missing values, understand the relationships with the target variable price and included normalization of numeric features to compensate for skewed data.  We also had a lot of non numeric values and performed one-hot encoding of these categorical variables creating almost 26k columns of data.

### Findings

1. Influential Factors on Car Prices

    Year of Manufacture: Is the most significant positive predictor of its price. Newer models tend to fetch higher prices.
    Mileage: Reading impacts the price negatively the most. Hence high mileage correlates with lower prices.
    There are also details on specific models you may want or prefer avoid.  These brands and models can be seen to have a large impact with very positive or negative effects on price.

2. Model Used and Performance

    Ridge Regression: Provided decent accuracy in our predictions with an R² of 0.61 or predicting 61% of the variance in price from our features. 
    

3. Recommendations for Inventory Management

    Newer Models bring in the most: Given the strong influence of the car's year, stocking newer models could be more profitable assuming margins are percentage based.  Also shopping for vehicles out of state for example in Oregon could also allow purchasing at a cheaper price (almost 10% for some models) then a higher resale value elsewhere.  
    Diverse Brands and Mileage: While lower mileage cars are valued higher, there is a market for higher mileage cars, suggesting a diverse range in odometer readings may appeal to a broader customer base.
    Special Attention to specific brands and models: The preference for Fords and  should be considered when selecting inventory.

### Conclusion

This type of data driven analysis at first might not seem usefull to a seasoned professional as the obvious indicators such as mileage, age and luxury models are known price drivers, however beyond it's basics it can be great for further insight into hidden market data such as leveraging out of state sales for specific models and more.  This data driven analysis also provides powerfull insights in what to avoid to remain profitable.  Data driven decision making will help dealerships reduce pricing risks by leverage better approaches to a more profitable inventory management in an ever changing market.  
