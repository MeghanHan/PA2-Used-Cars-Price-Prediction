# PA2-Used-Cars-Price-Prediction
Links to [prompt](https://github.com/MeghanHan/PA2-Used-Cars-Price-Prediction/blob/main/prompt_II.ipynb) and [images](https://github.com/MeghanHan/PA2-Used-Cars-Price-Prediction/tree/main/images)

To improve inventory of used car dealerships for the business to be more profitable, we built regression models to explore the relationship between used car features and price following the CRISP-DM framework. The test mean squared error is significantly smaller than the baseline mean squared error. We see the test mean squared error of the model improve as we add in more types of variables (quantitative, ordinal, nominal). But when selecting 6 features, the mean squared errors are the same across three major linear regression models. We also did grid search to select the best alpha for ridge regression. 
The findings are listed below:
- Used car prices are positively correlated with the number of cylinders, the size of the car and negatively correlated with the age and the mileage of the car.
- The better the condition of the car, the higher the price.
- Used cars of common colors (e.g. white, silver, grey, black) can sell for a higher price than less common colors (e.g. orange, purple, yellow). Black and white cars have the best resale value.
- Front-wheel-drive cars are less valuable than back-wheel-drive cars and four-wheel-drive cars.

Based on the findings, we have the following recommendations:
- Increase the inventory of full-size cars in good condition.
- Increase the share of cars that are made recently without a lot of mileage.
- Get cars with more cylinders for higher price.
- Pick common colors such as white, silver, grey and black and avoid unusual colors such as orange, purple and yellow.
- Reduce the number of front-wheel drive cars in the inventory.
