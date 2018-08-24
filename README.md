# Collaborative Filtering - User Based Regression
Collaborative Filtering: This approach builds a model from past behaviors, comparing items or users trough ratings, and in this case an User Based Regression technique is used to predict the missing values. The Grey Wolf Optmizer (GWO) is used to find minimum loss value. The function returns: the prediction of the missing data and the gwo solution.

* Xdata = Dataset Attributes. A matrix with users ratings about a set of items.

* user_in_columns = Boolean that indicates if the user is in the column (user_in_column = True) or in the row (user_in_column = False). The default value is True.

* pack_size = To find the weights, a metaheuristic know as Grey Wolf Optmizer (GWO) is used. The initial population (pack_size) helps to find the optimal solution. The default value is 25.

* iterations = The total number of iterations. The defaul value is 100
