# House-pricing
House price prediction
House price prediction is an important concept in the real estate industry. Thus, many researchers from different fields are interested in developing a regression model for the house price to obtain an accurate prediction and explore the factors affecting the house price.
The research started with data extraction, loading and cleaning. Then we proceed to Exploratory Data Analysis to further understand the available features in the data, the relationship that exist among the features and how it affects pricing. 
The following findings were made:
The house Prices ranges between 755000𝑚𝑎𝑥𝑎𝑛𝑑 34900 min with average Price of $180921.195890 which is the same as the train dataset
Although there were about 80 features, in the dataset, only 10 are most important and contributes largely to the Sales price 'OverallQual', 'YearBuilt', 'YearRemodAdd', 'TotalBsmtSF', '1stFlrSF', 'GrLivArea', 'FullBath', 'TotRmsAbvGrd', 'GarageCars', 'GarageArea'.
Sales under Normal condtion gives best price
Increase in Quality also increases Sales Price
Increase in OverallQuality also increases Sales Price
price rises with years, meanwhile 1990 experienced a significant hike in price
Sales Price doesnot give a normal or Gaussian distribution
Training Models
The dataset was Splitted into 80% for training and 20% for testing
The generalized model must neither experience under fitting nor over fitting, for us to get the best result. This work tested seven different models: LinearRegression, Ridge, Lasso, ElasticNet, DecisionTreeRegressor, Support vector Regressor (SVR), RandomForestRegressor, and xgboost. RandomForestRegressor was found to be the best, giving the highest training and test accuracy and with smallest RMSE
