# MLInit
MLInit is a comprehensive python-notebook based framework for data wrangling and exploratory analysis. 
1. It provides an easy to use ipywidget based GUI Interface to input the data, label and for customizations
2. Automatically Identifies the type of problem (regression/classification), type of features(numerical/categorical), clean data via regex and transforms data.
3. Visualizes data in various forms for effective EDA
4. Detects skewness in data distribution, performs multicollinearity checks, dimensionality reduction test and also provides missing datapoints report.
5. Performs imputation based on various methods like KNN, Bfill/Ffill, iterative, simple imputation and most frequent class
6. Performs stratification based on top correlated features and reports reduction in error in comparison to random split
7. Performs modelling suggestion based on regression, classification problem type and allows user to tune the model hyper parameters and train. 
8. Reports accuracy via R2, RMSE for regression and F1, AUC for classification
