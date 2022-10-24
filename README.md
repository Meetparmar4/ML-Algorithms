# ML-projects
Worked on some basic datasets and problems for learning these ML algorithms.

## Logistic Regression

-  Titanic Dataset. 
-  Learned to deal with missing values by replacing them with mean value based on a categorical features from another column.
-  Used getdummies function for replacing categorical variables into numbers which can be used to train the model.
-  Predicted whether a person survived the Titanic or not based on the various attributes of the passengers.

## Linear Regression

- Worked on an Ecommerce website dataset to find what factors affect the amount of money the customers spend on the website.
- Selected the determining features by visualisations which showed correlation to the target variable. The chosen independent features were all numeric for which I used the linear regression algo to predict the dependent feature.
- Used metric errors like MSE, RMSE and MAE to check the performance of the model and a coefficent matrix.

## PCA

- Principal component analysis (PCA) is a technique for reducing the dimensionality of such datasets, increasing interpretability but at the same time minimizing information loss. It does so by creating new uncorrelated variables that successively maximize variance.
- HOW DO YOU DO A PRINCIPAL COMPONENT ANALYSIS?
   1.  Standardize the range of continuous initial variables
   2.  Compute the covariance matrix to identify correlations
   3.  Compute the eigenvectors and eigenvalues of the covariance matrix to identify the principal components
   4.  Create a feature vector to decide which principal components to keep
   5.  Recast the data along the principal components axes
- Worked on breast cancer dataset which has 30 columns which are all important to determine whether the cancer is malignant or bening.
- Learned to use the Principal Component Analysis technique to reduce the dimensions of the datasets.

## KNN

- Used an abstract dataset made for making beginners familiar with the algorithm.
- Scaled the numeric data in columns using standard scaler
- Used the elbow method to pick a good K value, also created a for loop that trains various KNN models with different K values.
- Made a list keep a track of error rate for each of these models with visualisation.


## SVM

- Used the Iris dataset 
- After some EDA, I directly trained the model on SVM algorithm and checked the performance using classification report.
- Later, I adjusted the hyperparameters by doing a grid search to find out the best possible values for c and gamma and chose the best parameters.
- Again tested the performance using classification report and confusion matrix.

## Random Forests and Decision Trees

- Worked on lending club dataset with columns like Credit policy of the club, FICO scores and the customers being able to pay off their debt or not.
- Performed visual analysis on the data to understand it better.
- Trained Decision tree and random forests algorithms to predict whether the customers are able to pay their loans or not based on their other features
- Retrained model with the best K value and checked the performance of the predictions with a classification report.
- Used classification report and confusion matrix to see the performance of the models.
