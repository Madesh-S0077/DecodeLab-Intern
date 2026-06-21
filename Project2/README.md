*Handling Imbalanced Dataset
***-> SMOTE Technique is used to create synthetic data samples of minority class
**Pipeline1:
     Model : LogisticRegression
     Cross-Validation: 5
     StandardScaler: To standarize the amount column
**Pipeline2:
     Model: RandomForestClassifier
     Cross-Validation: 5
     Standardization is not needed since RandomForestClassifier is not influnced by values of features.
**Evaluation:
     GridSearchCV: It is used for hypertuning the best parameters
     Precision, Re-call, Confusion-Matrix are used to evaluate the model using the hyperparameters.
