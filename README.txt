# House Prices - Advanced Regression Techniques
# Tal Brender, Jonathan Enav, Efrat Isack
# 18/Feb/2024

# Intro
This repository contains the code that participated in the global Kaggle competition, House Prices: Advanced Regression Techniques.
The submission achieved 115th place with a score of 0.11800.
Link:
https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/submissions

# Main Code
JET Final.ipynb is a Jupyter Notebook that contains the Exploratory Data Analysis (EDA) and the code used for the final submission.

# Additional Info
JET Kaggle Final.pptx contains the final presentation for the project.

# Submission
submission_Final.csv is the file used for the final submission, which achieved a score of 0.11800.

Pipeline:
1. DropID: Removes the unique identifier column, which isn't useful for model training.
2. RemoveNAsCol: Eliminates columns with a high percentage of missing values to reduce noise.
3. ImputeNAsRow: Fills in missing values in rows using appropriate imputation techniques.
4. FeatureEngineering: Creates features to improve model performance.
5. HandleCategoric: Converts categorical variables where needed into numerical format suitable for the model.
6. DimReduction: Reduces the number of features to avoid overfitting and improve computational efficiency.
7. CatBoostRegressor: Applies the CatBoost algorithm, a powerful gradient boosting method, for regression tasks.




