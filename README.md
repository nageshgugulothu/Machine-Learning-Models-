# Machine-Learning-Models-
Linear Regression Model --Logistic Regression -- MultiLinear Regression -- Polynomial Regression
=================================================================================================
Supervised Learning
In supervised learning, the training data you feed to the algorithm includes the desired solutions, called labels.

A typical supervised learning task is classifcation. The spam filter is a good example of this: it is trained with many example emails along with their class (spam or ham), and it must learn how to classify new emails.

Another typical task is to predict a target numeric value, such as the price of a car, given a set of features (mileage, age, brand, etc.) called predictors. This sort of task is called regression. To train the system, you need to give it many examples of cars, including both their predictors and their labels (i.e., their prices).

Linear Regression
Linear regression is one of the simplest supervised learning algorithms in our toolkit. Linear regression—and its extensions—continues to be a common and useful method of making predictions when the target vector is a quantitative value (e.g., home price, age).

Linear regression models linear relationship among variables. An example of a linear relationship would be the number of stories a building has and the building’s height. In linear regression, we assume the effect of number of stories and building height is approximately constant, meaning a 20-story building will be roughly twice as high as a 10-story building, which will be roughly twice as high as a 5-story building.

More generally, a linear model makes a prediction by simply computing a weighted sum of the input features, plus a constant called the bias term (also called the intercept term) as shown below:
𝑦̂ =𝜃0+𝜃1𝑥1+𝜃2𝑥2+...+𝜃𝑛𝑥𝑛
 
where

𝑦̂ 
  is the predicted value
𝑛
  is the number of features
𝑥𝑖
  is the ith feature value
𝜃1,𝜃2,...,𝜃𝑛
  are feature weights (parameters or coefficients) and  𝜃0
  is the bias term (or intercept)
Why are we learning linear regression?

widely used
runs fast
easy to use (not a lot of tuning required)
highly interpretable
basis for many other methods
Univariate (Simple) Linear regression
Linear regression with a single variable or feature is called univariate linear regression. The output of linear regression is an estimate of the outcome variable (aka target).
