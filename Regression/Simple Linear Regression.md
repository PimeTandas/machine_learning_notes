Simple Linear Regression (SRL) is the most simple bare basic form of linear regression. It is simple as it only looks at one independent variable and one dependent variable.

It looks to estimate a relationship between two continuous variables by fitting a linear relationship to the data.
The equation for simple linear regression is simply the equation of a line:

$$ \text{Simple Linear Regression Equation:} \\  Y = \beta_0 + \beta_1 X + \varepsilon $$

Where:
- (Y) is the dependent/target variable.
- (X) is the independent variable/ feature.
- (beta_0) is the intercept.
- (beta_1) is the coefficient for the (X) variable, that determines the slope of the graph.

The goal of simple linear regression is to estimate the values for the beta_0 and beta_1 that minimize the sum of the squared differences. The mean squared is calculated like shown:

$$ \text{MSE} = \frac{1}{n} \sum_{i=1}^{n} (y_i - \hat{y}_i)^2 $$
Where:
- (n) is the number of data points.
- ($yi$) is the actual value of the target variable.
- $(\hat{y_i})$ is the predicted value of the target variable.

Basicly we sum the squared difference between the predicted values for y and the actual values for y, then use this to calculate the mean.