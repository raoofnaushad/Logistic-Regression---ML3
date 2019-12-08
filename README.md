---

Machine Learning using Python
Part-3
Now let's walk through each every types of machine learning in detail.
We have studied that there are basically 3 types of machine learning. Supervised learning, Unsupervised learning, Reinforcement learning.
Let us learn one by one
Supervised learning:

Supervised learning as the name indicates the presence of a supervisor as a teacher. Basically supervised learning is a learning in which we teach or train the machine using data which is well labeled that means some data is already tagged with the correct answer. After that, the machine is provided with a new set of examples(data) so that supervised learning algorithm analyses the training data(set of training examples) and produces a correct outcome from labeled data
Now there are basically 2 subcategories of supervised learning:
Classification : Defined labels || Output should be either of some targets.
Regression : No labels are defined || Output can be any value.



We will study Classification in detail now.
Classification
Logistic Regression
Logistic regression is a classification machine learning algorithm that deals with the two-class problems.
Logistic Regression works with logistic function. It is also called sigmoid function. This function graphically represent an S-shaped curve. 
The working of the logistic regression is that with the corresponding data set programmers go on search for the optimum coefficient value in order to predict the new values for the new inputs given.
The search process continously change the coefficient value until the error in minimum so as to predict the new input values.
Logistic regression equation is just like linear regression equation the main difference is that the output value modeled is binary in nature.
 b0-intercept, b1-coefficient of x1, p is the predicted outputLet us say a coefficient is already given. So we know the values of b0 and b1. In order to make the prediction put the input values to the above equation we will get the output value.
But modeling our machine learning algorithm for logistic regression is finding the optimum values of the coefficient with minimal error to produce the precised output.
So how do we find the coefficient values? What is the best coeffiecient?
Coefficient for the model is generally find out using Maximum-likelihood estimation which is a common learning algorithm.
The best coefficient is that value which predicts a value very close to 1(for the default class) and very close to 0( for the other class). 
We use Stochastic Gradient Descent to update the coefficient. For each iteration the coefficient value is updated using the equation.


We can use scikit learn, a python library that can be used for machine learning for logisitc regression. let's see how it can be used. 
Check out my github and read through the jupyter notebook to know how 1) intialising a logistic regression model. 2) Fitting model 3) Making predictions and also 4) Check the probability of prediction.




---

Thank you for reading my blog. Have a nice future ahead.
 Resources:  Google, Geeks for Geeks, Udemy


---
