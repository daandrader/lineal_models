# Lineal Regression using regularization l1 and l2
Using the California Housing Dataset (CHD) to implement a predictive model of the Median House Value throug a lineal regression application. All the info of the dataset can be found [here](https://www.dcc.fc.up.pt/~ltorgo/Regression/cal_housing.html).
Considering the lineal regression assumtions the lineal model is constructed using regularization, more specifically comparing the result of l1 and l2 regularization using scikit-learn.

## Changes
- The CHD dataset is featched using the built-in functionality of scikit-learn.
- Multicolinealuty is studied througout the correlation of the features variables and VIF indicator.
- Ridge regresion and Lasso regresion are implemented using GridsearchCV optimizing the parementers of each funtion.
- Normality of the residuals are tested using statistical tests and graphycally.
- A comparison of the R2 and the MSE evaluation metrics.

## TODO

- Migrate Ridge and Lasso funtions to their Cross validation respectives, in order to implement Cross validation in the pipeline of the algorithm.
