---
date: 2022-02-27T05:38
---

# ISLR 2

There is no free launch in statistics. No one method dominates other methods in all types of datasets.

**Variance** : the amount by which f would change when using a different training dataset.
**Bias** : the error that is coming from the approximation of a real-life problem.

## Installing a package in Kaggle

In order to use a package that is not available in Kaggle, you need to download it manually. Since Kaggle unzips all types of compressed files, as a workaround, you need to compress the file with a password. After uploading the file as a dataset you can unzip it with the password you used in the compression step. Finally, you can install the package with default R commands.

*Reference* : [Kaggle](https://www.kaggle.com/returnofsputnik/how-to-use-external-uploaded-r-libraries-on-kaggle/)


## Linear Regression
 * The first step in a multiple regression analysis is to compute the F-statistic and to examine the associated p-value.
 * Variable selection as a second step. Model selection criterias : Mallow's $C_p$, Akaike information criterion (AIC), Bayesian information criterion (BIC), and adjusted $R^2$.
 	* Forward selection
    * Backward selection
    * Mixed selection
* Model fitting, the third step.
* Finally, prediction

When predicting, you need to consider model bias for errors.
Prediction intervals vs Confidence intervals.
**confidence interval** : Quantify the uncertainity surrounding the average output over a larger number of samples.
**prediction interval** : Quantify the uncertainity surrounding the output for a particular sample.

**hierarchical principle** : if we include an interaction in a model, we should also include the main effects, even if the p-values associated with their coefficients are not significant.

Plotting a residual errors is a good way to show that whether the model is good.

**variance inflation factor** :

