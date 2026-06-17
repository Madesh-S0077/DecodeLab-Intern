### This Repository contans a project that includes cleaning and analysis of a dataset (Product-Sales-Region)
#### Cleaning: A column - named promotion includes 370 missing values.
#### One-hot-encoding is used to convert nominal categorical values into numerical values
#### Imputation: Used KNNImputer to impute the missing values using other columns
#### Analysis - Checking for multicollinearity
#### Multicollinearity check is done throught correlation matrix and columns whose correlation values is more than 0.80 - Either one of the column is dropped
#### Output - Finally, The cleaned dataset is given as output that can be used by ML models.
