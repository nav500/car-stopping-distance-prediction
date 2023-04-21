# Car stopping distance prediction based on speed

The model predicts car stopping distance based on the car's speed. The model is a univariate linear regression model. The car's speed is a feature, and the stopping distance is the target value.

The model uses a dataset collected in 1930 and published by Wiley. The dataset contains 50 rows.

# The model

The model $f$ is represented as

$$ f_{w, b}(x) = wx + b $$

where $w$, $b$ are weight and bias respectevely.

$y$ is the actual target value.

$$ \hat{y} = f_{w,b}(x) $$

$\hat{y}$ is the predicted output by the model.

There are 50 training examples.

# Algorithm 

Gradient descent algorithm is used to fit data to the model. Gradient descent (GD) is an iterative first-order optimisation algorithm used to find a local minimum/maximum of a given function. This method is commonly used in machine learning (ML) and deep learning(DL) to minimise a cost/loss function (e.g. in a linear regression)

# Libraries used

* Numpy
* Pandas
* Matplotlib
