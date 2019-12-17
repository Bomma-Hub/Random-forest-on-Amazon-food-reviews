# Random-forest-on-Amazon-food-reviews
Implementation of random forest on Amazon food reviews
--------------------------------------------------------------
Random Forest:
•	It is a popular bagging technique.
•	A large number of relatively uncorrelated models (trees) operating as a committee will outperform any of the individual constituent models
•	The low correlation between models is the key.


RF  =  D.T (Decision tree) + Bagging + Col. Sampling

•	Each model built on different sample of data.
For classification : Majority Vote
For Regression : MSE ( Mean Squared Error ) , MAE (Median absolute Error).

Single D.T (Decision Tree )  las Low Bias and High Variance (As change in features will change the behavior of the model).

Bunch of Low Bias and High Variance Model club to form a Low Bias and reduced Variance model

Libraries used:
1.WordCloud
2.PILLOW : A library is a package that enables image reading . 


XGBOOST :

 
1.	In any machine learning technique , the main causes of difference in actual and predicted values is due to Noise, variance and Bias.
2.	Ensemble model reduce Variance and Bias (As Noise is irreducible).
3.	Bagging is a simple ensembling technique in which we build many independent predictors/models/learners and combine them using some model averaging techniques. (e.g. weighted average, majority vote or normal average).
4.	Boosting is an ensemble technique in which the predictors are not made independently, but sequentially.
5.	This technique employs the logic in which the subsequent predictors learn from the mistakes of the previous predictors. Therefore, the observations have an unequal probability of appearing in subsequent models and ones with the highest error appear most.
 
 










