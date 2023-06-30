# Bike-Sharing-Demand-Prediction


# Rented Bike Count Analysis:
This repository contains the analysis of the rented bike count dataset. The analysis aims to explore the factors influencing the bike rental count and develop predictive models for accurate bike count estimation.

# Dataset:
The dataset used for the analysis contains information on various features such as date, hour, weather conditions, and holiday status. It also includes the target variable, which is the rented bike count.

# Analysis Steps:

**Data Exploration:** Perform exploratory data analysis to gain insights into the dataset, identify patterns, and understand the distributions and relationships between variables.

**Data Preprocessing:** Clean the data by handling missing values, removing outliers, and encoding categorical variables.

**Feature Engineering**: Create new features or manipulate existing features to minimize feature correlation and improve model performance.

**Feature Selection:** Use techniques like VIF (Variance Inflation Factor) to identify and select important features for the predictive models.

**Model Building:** Train and evaluate various regression models, such as Linear Regression, Lasso Regression, Ridge Regression, Decision Tree Regressor, RandomForestRegressor, XGBRegressor, etc.

**Model Evaluation:** Assess the performance of the models using evaluation metrics like Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared (R2) score.

**Hyperparameter Tuning:*8 Fine-tune the model hyperparameters using techniques like Grid Search or Random Search to improve the model's performance.

**Conclusion:** Summarize the key findings from the analysis, including the most accurate model and the significant features affecting the bike rental count.

# Results

Here are the key findings from the analysis:

The XGBRegressor model, after hyperparameter tuning, achieved the highest accuracy with a score of 95.4%.

Features such as hour, temperature, humidity, wind speed, and solar radiation showed strong correlations with the rented bike count.

The decision tree regressor and random forest regressor also performed well, achieving accuracies of 86.4% and 92.5% respectively.
