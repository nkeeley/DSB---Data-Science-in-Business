# DSB - Data Science in Business

Language types: Python

This repository contains several assignments and projects related to predictive modeling (using machine learning tecniques), data munging, and data visualization. For the capstone project, my team and I submitted a model to an expired Kaggle competition: the Microsoft Malware Classification Challenge.

### Core Code_17DEC2021.ipynb (Microsoft Malware Classification Challenge Project)

- Background: In 2015, Kaggle created a competition that sought to accurately classify which computers would be infected by malware. The datasets used and a more detailed description of the competition can be found at https://www.kaggle.com/competitions/microsoft-malware-prediction/data.
- Method: We used a Random Forest regressor, ridge regression, and a weighted ensemble of both models.
- Results: Our Random Forest regressor performed the best, with an AUC score of .71 for the validation data, but only .58 on the test data. However, we were confident that with further optimization of hyperparameters, this score could have improved significantly. Additionally, the project allowed us to gain insight on feature importance and ways to reduce the likelihood of malware presence in computers.
- Associated files: In "Core Code_17DEC2021", I munged the data into a form that was suitable for analysis. This included strategically imputing values for categorical/continuous variables, isolating and renaming key features, and cleaning the dataset (of NA and redundant values). Finally, I fit a Random Forest regressor on the data to predict malware estimates. Our team's results and insights can be found in "Final Presentation.pptx".

### CarvanaStarter.ipynb

This is a template file created by the professor for us to practice cleaning, engineering, and modeling on a Carvana dataset to predict which vehicles were "good buys." Modeling techniques included regularized logistic regression, decision trees, random forests, and boosted trees.

### DiamondStarter.ipynb

This is a template file created by the professor for us to practice cleaning, engineering, and modeling on a dataset of diamonds to predict diamond price. Techniques included OLS regression through patsy syntax, logarithmic transformations, interaction effects, and linear splines.

### SabrBracketing.ipynb

This is a template file created by the professor for us to practice cleaning, engineering, and modeling on a dataset of model results for baseball players. Techniques included choosing accuracy/scoring metrics, as well as ensembling models.

### Nick K Analysis.ipynb

This is a template file created by the professor for us to practice producing predictive models to predict the outcome of the Obama/Clinton primary in 2008. Techniques included data cleaning/imputation, regularized linear regression, decision trees, and random forests.

### BikeStarter.ipynb & Boosted_Tree.ipynb

This is a template file created by the professor (as well as an adapted notebook produced by me) for us to practice producing tree-based models to predict shared bicycle demand in DC. Techniques included "pickling" models, boosted tree models, and grid-search hyperparameter optimization.

### CarvanaStarter-II.ipynb

This is a template file created by the professor in which we revisted the Carvana dataset with new scoring metrics. Techniques included AUC/ROC evaluation, as well as using a Gini Index and other scoring metrics.

### HospitalDischargeBinary.ipynb

This is a template file created by the professor in which we investigated hospital discharge predictions. Techniques included dimensionality reduction through Principle Component Analysis (PCA), regularized regression/random forests with PCA values, and an introduction to neural networks.




