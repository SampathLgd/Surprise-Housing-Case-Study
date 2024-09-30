# Surprise-Housing-Case-Study


## Abstract

Data is provided by the United States-based company Surprise Housing. The goal 
is a housing price prediction model for Australia. The task is to apply data 
analytics for determining why different factors affect house prices, thereby 
allowing the company to strategically determine which properties to buy at 
below-market value and sell when priced higher. The research stages involved are 
cleaning data, exploratory data analysis (EDA), building models with machine 
learning, and assessing the model . 

------
## Objective 
This study focuses mainly on the prediction of housing prices in Australia using all 
independent variables from the dataset available. The model will serve as a means 
to determine how Surprise Housing management can refine its business strategy 
based on areas yielding higher returns after it has been directed towards them. 

------
## Introduction 
Surprise Housing, a US-based company, seeks to enter the Australian housing 
market by identifying properties that can be bought below their market value and 
sold at a profit. Using data analytics, the company aims to create a predictive 
model to evaluate housing prices based on collected sales data. This model will 
help guide their investment strategies and maximize profitability.

-----

## Methodology 

### Creation of Virtual Environment: 
●  A virtual environment is created to ensure a clean development setup. 

### Import Dataset / Read CSV: 
●  The dataset containing historical house sales data is imported for analysis. 

### Data Cleaning: 
●  The dataset is processed to handle missing values and outliers, and 
categorical variables are converted to numerical representations. 

### Data Preparation: 
●  The feature set XXX is created by dropping the target variable 
SalePrice  , while yyy is assigned the  SalePrice  column. 
●  The numerical columns are standardized using  StandardScaler  . 
●  The dataset is split into training and testing sets, with 25% allocated for 
testing. 

### Building and Evaluating ML Models: 
●  Ridge Regression  : 
○  A Ridge regression model is trained with hyperparameter tuning via 
GridSearchCV  . The optimal alpha found was 0.0001. 
○  The model demonstrates an R2 score of 1.00 for the training set and 
0.89 for the test set, indicating excellent performance with very low 
RMSE values. 
●  Lasso Regression  : 
○  A similar procedure is followed for Lasso regression, with the best 
alpha determined to be 0.05. 
○  The Lasso model shows R2 scores of 0.76 for the training set and 0.74 
for the test set, with higher RMSE scores compared to Ridge.

-----
## Conclusion 
The models developed in this study provide significant insights into the factors 
influencing housing prices in Australia. Ridge regression outperformed Lasso 
regression, with higher R2 scores and lower RMSE values. The predictive 
capabilities of these models can assist Surprise Housing in making strategic 
decisions regarding property investments. Further refinements, including the 
integration of additional data, may enhance model accuracy and profitability.
