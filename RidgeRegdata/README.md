# Ridge Regression
Ridge regression is a type of linear regression with L2 regularization. It is used in machine learning primarily to address issues like overfitting and multicollinearity in linear models. Ridge regression introduces a regularization term that penalizes large coefficients, helping to stabilize the model and prevent overfitting. This regularization term, also known as the L2 penalty, adds a constraint to the optimization process, influencing the model to choose smaller coefficients for the predictors.
Similarly, It helps stabilize the model and improves generalization to new data and handle situations where predictor variables are strongly correlated. Like in the below figure. 
# Why to use Ridge Regression
Some of the important reasons to use Ridge Regresssion are:
a. To reduce multicollinearity 
b. To handle the overfitting
c. To balance bias and variance
# My Experience
I took the mtcars datasets then I applied both linear regression and ridge regression .
Similarly , I calculated R2 score for both model and results were totally surprising. The R2 of ridge regression was 0.75 and of linear regression was 0.54. So ridge regression helps to stabilize the model.
