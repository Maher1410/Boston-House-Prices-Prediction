# Boston-House-Prices-Prediction

This project utilizes a variety of machine learning algorithms to predict house prices from the Boston Housing dataset. The Boston Housing dataset is a widely used dataset in machine learning and data science, collected by the U.S Census Service concerning housing in the area of Boston Mass.

The dataset includes 14 features: 
- CRIM: per capita crime rate by town
- ZN: proportion of residential land zoned for lots over 25,000 sq.ft.
- INDUS: proportion of non-retail business acres per town
- CHAS: Charles River dummy variable (1 if tract bounds river; 0 otherwise)
- NOX: nitric oxides concentration (parts per 10 million)
- RM: average number of rooms per dwelling
- AGE: proportion of owner-occupied units built prior to 1940
- DIS: weighted distances to five Boston employment centres
- RAD: index of accessibility to radial highways
- TAX: full-value property-tax rate per $10,000
- PTRATIO: pupil-teacher ratio by town
- B: 1000(Bk - 0.63)^2 where Bk is the proportion of blacks by town
- LSTAT: % lower status of the population
- MEDV: Median value of owner-occupied homes in $1000's

The project begins with importing the necessary libraries and loading the data from a CSV file. We then perform an Exploratory Data Analysis (EDA) to get an understanding of the dataset. The EDA involves checking the shape of the dataset, checking for null values, viewing basic statistical details, and checking the correlations among the features using a heatmap. 

The next phase involves checking for linear relationships between each feature and the target variable (MEDV), which provides a more detailed look at the data. We also check for outliers in the data using box plots. 

Once we have a clear understanding of the data, the process of building models to predict the prices begins. The data is split into a training set and a testing set. Four different models are trained and tested: 

1. Linear Regression
2. Decision Tree
3. Random Forest
4. XGBoost

Each model is trained using the training set, and then the performance of the models is evaluated using the testing set. The performance is evaluated using the R² score, which gives the proportion of the variance in the dependent variable that is predictable from the independent variable(s). In other words, it provides a measure of how well the regression predictions approximate the real data points. 

The results show that the XGBoost model performed best with a training accuracy of 99.99%, a testing accuracy of 91.05%, and an overall model accuracy of 98.43%.

This project provides a clear example of how to perform a full cycle of data science tasks, from initial data loading and exploration, through pre-processing and visualization, to training and evaluating machine learning models. 

Remember to check for any specific setup instructions or dependencies required to run this project, such as Python libraries or data files.
