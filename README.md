# Feature-engineering-with-PolynomialFeatures
In simple words, Polynomial features are those features created by raising existing features to an exponent. This is a type of feature engineering i.e. creating of new input features based on existing ones. In the current FIFA dataset there were a few categorical variables which were modified/encoded to numerical variables. First the LinearRegression module from sklearn was implemented which gave less accuracy. The number of columns in the dataset is less. Therefore, polynomial and interaction features are easier to be created and handles by the model. There are 3 models built based on linear regression:
1. Linear regression with the OLS method
2. Linear regression based on polynomial features(degree=3)
3. Linear regression based on polynomial features(interactions_only attribute)
R-squared metric was use dfor evaluating each of these models on the split test data(80:20)
The second model gave the highest R2 score and was then used to predict the values of the test dataset given separately. After submission of the csv file, 0.984 score was achieved which assured that the model based on polynomial features was the best for the given dataset overall.
