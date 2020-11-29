
This tutorial is going be to dedicated to understanding how to properly manipulate data sets and get data in a useful form. Since we are going to be using large data sets throughout all of the future tutorials this is very important to understand.
### This example is dedicated to understanding how to properly manipulate data sets and get data in a useful form using Linear Regression.

## Install the following packages: pip install _____    (replace _____ with the package names below)
- tensorflow
- sklearn
- pickle
- numpy
- keras

- ⚡ In this specific example I will be implementing the linear regression algorithm to predict students final grade based on a series of attributes. To do this I need some data!

We are going to be using the Student Performance data set from the UCI Machine Learning Repository.
https://archive.ics.uci.edu/ml/machine-learning-databases/00320/


### 📺 Linear Regression is essentially just a best fit line. Given a set of data the algorithm will create a best fit line through those data points.

This line can be defined by the equation y = m*x + b.

m is the slope. Meaning how much the y value increases for each x value.

b is the y intercept. Where the line crosses the y axis.

We can determine the slope(m) of the line by picking two points on the line (p1 and p2) and using the following equation: m = (y2 - y1) / (x2 - x1)

Once the computer has generated this line it will use it to predict certain values.

Note: The examples above are done in 2D space. In reality most of our best fit lines will span across multiple dimensions and therefore will have multiple slope values.

In this tutorial I will need to install one more module called matplotlib. I will also be using the module pickle that does not need to be installed.

Similarly to before I will activate our environment using activate "environment name" and then type pip install matplotlib in the command prompt.


