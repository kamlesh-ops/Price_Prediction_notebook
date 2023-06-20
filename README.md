# Ames House Price Prediction

In this notebook, different approaches like exploratory analysis, data visualization, feature engineering, and feature selection have been employed to understand the dataset. Finally, different ML algorithms like Random Forest, Decision Trees, and boosting algorithms like Gradient Boosting have been implemented to predict the prices.  

This is a starter notebook and is also meant for learning purposes for beginners.  
Link: [Dataset](https://www.kaggle.com/datasets/prevek18/ames-housing-dataset)   

## About Dataset
The dataset contains 82 feature columns and 2930 examples(rows). It describes the sales of residential units in Ames, Iowa starting from 2006 until 2010.  

## Notes
1. The model performances are evaluated using the MAE(Mean Absolute Error) metric, for fundamental understanding of the working of various models.
2. The linear regression model has been extended to Ridge and Lasso regression techniques.

## Models
Simple Linear Regression, Lasso and Ridge Regression, Decision Trees, Random forests and XGBoost are the algorithms used for training the models.

## Comparison among algorithms
![Screenshot 2023-06-20 121646](https://github.com/kamlesh-ops/Price_Prediction_notebook/assets/101917668/f827acce-c661-4d1e-8f83-3eeaccb7a2d8)  

The maximum MAE score is for Decision Trees and the minimum is for XgBoost. This suggests that XgBoost is the best model in this approach and Decision Trees is the worst.



