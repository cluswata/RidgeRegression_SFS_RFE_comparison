# RidgeRegression_SFS_RFE_comparison

Comparisons of Ridge regression, Recursive Feature Elimination (RFE) with Lasso, and Sequential Feature Selection (SFS) with Lasso modeling of red wine chemical compositions to predict its quality

Lower MSE and higher R-squared indicate better model performance. However, Ridge regression has more variables whose VIF<10 indicating absence of multicollinearity, which problem ridge regression is trying to solve by shrinking the coefficients. RFE with Lasso eliminates the least important features while SFS with Lasso fits the model by adding or removing features based on performance improvement thereby selecting features that maximize model performance. I am choosing SFS with Lasso because it’s a parsimonious model and it is very easy to interpret. 
