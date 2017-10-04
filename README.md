# House-Prices-Advanced-Regression-Techniques


Our goal is to transform all of our data into numeric, while preserving as much information from the categoric variables as we’re going to use a gradient boosting method (XGBoost). As XGBoost has trouble with extrapolation we will use ridge, lasso and elastic-net regularization, which will also account for a lot of the multicollinearity in the data. Once we have predictions from all 4 regressors we can average the results to get an accurate estimate. We’ll go more in depth on why we chose these methods and how we’ll use them later on.
