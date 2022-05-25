# DSB - Data Science in Business

Language types: Python

This repository contains several assignments related to predictive modeling (using machine learning tecniques), data munging, and data visualization throguh Tableau. For the capstone project, my team and I submitted a model to an expired Kaggle competition: the Microsoft Malware Classification Challenge.

### Core Code_17DEC2021 (Microsoft Malware Classification Challenge Project)

- Background: In 2015, Kaggle created a competition that sought to accurately classify which computers contained malware. The dataset provided was about 500GB. 
- Method: We used a Random Forest regressor, ridge regression, and a weighted ensemble of both models.
- Results: Our Random Forest regressor performed the best, with an AUC score of .71 for the validation data, but only .58 on the test data. However, we were confident that with further optimization of hyperparameters, this score could have improved significantly. Additionally, the project allowed us to gain insight on feature importance and ways to reduce the likelihood of malware presence in computers.
- Associated files: In "Core Code_17DEC2021", I munged the data into a form that was suitable for analysis. This included strategically imputing values for categorical/continuous variables, isolating and renaming key features, and cleaning the dataset (of NA and redundant values). Finally, I fit and optimized a Random Forest regressor on the data to predict malware estimates. Our team's results and insights can be found in "Final Presentation.pptx".
