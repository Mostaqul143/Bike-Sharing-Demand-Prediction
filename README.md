# Seoul-Bike-Sharing-Demand-Prediction

Welcome to my Seoul Bike Sharing Demand Prediction project! This repository contains the analysis of the rented bike count dataset. The analysis aims to explore the factors influencing the bike rental count and develop predictive models for accurate bike count estimation.

## Features

- Visualizations of bike rental count by hour, weather conditions, and holiday status.
- Comparative analysis of bike rental count across different days and months.
- Breakdown of bike rental count by various features.
- Trends in bike rental count over time.

## Insights

## Rented Bike Count Analysis:
This repository contains the analysis of the rented bike count dataset. The analysis aims to explore the factors influencing the bike rental count and develop predictive models for accurate bike count estimation.

## Dataset:
The dataset used for the analysis contains information on various features such as date, hour, weather conditions, and holiday status. It also includes the target variable, which is the rented bike count.

## Analysis Steps:

**Data Exploration:** Perform exploratory data analysis to gain insights into the dataset, identify patterns, and understand the distributions and relationships between variables.

**Data Preprocessing:** Clean the data by handling missing values, removing outliers, and encoding categorical variables.

**Feature Engineering**: Create new features or manipulate existing features to minimize feature correlation and improve model performance.

**Feature Selection:** Use techniques like VIF (Variance Inflation Factor) to identify and select important features for the predictive models.

**Model Building:** Train and evaluate various regression models, such as Linear Regression, Lasso Regression, Ridge Regression, Decision Tree Regressor, RandomForestRegressor, XGBRegressor, etc.

**Model Evaluation:** Assess the performance of the models using evaluation metrics like Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared (R2) score.

**Hyperparameter Tuning:** Fine-tune the model hyperparameters using techniques like Grid Search or Random Search to improve the model's performance.

**Conclusion:** Summarize the key findings from the analysis, including the most accurate model and the significant features affecting the bike rental count.

## Results

Here are the key findings from the analysis:

- The **XGBRegressor** model, after hyperparameter tuning, achieved the highest accuracy with a score of **95.4%**.
- Features such as hour, temperature, humidity, wind speed, and solar radiation showed strong correlations with the rented bike count.
- The **Decision Tree Regressor** and **Random Forest Regressor** also performed well, achieving accuracies of **86.4%** and **92.5%** respectively.

## How to Access

To view the analysis, follow these steps:

1. **Clone the Repository**: Clone this GitHub repository to your local machine.
2. **Open Jupyter Notebook**: Open the Jupyter Notebook file (`bike_sharing_demand_prediction.ipynb`) included in the repository.
3. **Run the Notebook**: Run the notebook cells to execute the analysis and view the results.
4. **Explore**: Explore the findings and insights presented in the notebook.

## Data Sources

The data used in this analysis is sourced from the Seoul Bike Sharing Demand dataset, which contains information on bike rentals including date, hour, weather conditions, and holiday status.

## Feedback

If you have any feedback or suggestions for improving the analysis, feel free to open an issue or submit a pull request. Your input is valuable and helps enhance the quality of this project.
