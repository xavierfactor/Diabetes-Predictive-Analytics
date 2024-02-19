Python project that utilize ML models to predict diabetic status of some 250,000 survey volunteers. Data has binary target and 21 numerical features and was imbalanced 86% vs 14% dataset in favor of the negative target class.

Data Source: https://www.kaggle.com/datasets/alexteboul/diabetes-health-indicators-dataset?resource=download

Methodology: Stratified train test split was performed with 20% of the data reserved for the test and the remaining 80% utilized for model selection as a training validation set. GridSearchCV was performed with 5 fold cross validation to determine the optimal hyperparameters for each model.
