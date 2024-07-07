# Real-Estate-Price-Predictions
## Linear Regression, Gradient Boosting and Multi-layer Perceptron (MLP)

This code is a comprehensive data preprocessing and modeling pipeline for real estate price prediction. The dataset contains information about various properties, including price, area, number of rooms, district, and other features.

## Key Steps:
### Data Loading and Initial Exploration:

Load the dataset and display initial rows.
Remove extreme outliers and invalid entries from key columns.

### Feature Engineering:

Create a new target variable (nmAr) representing the price per square meter.
Handle missing values and outliers in various columns, such as property area, balcony area, number of rooms, and property condition.
Transform categorical variables (e.g., district, heating type) into dummy/indicator variables.
Generate new features, such as average district price and day of the week from creation date.

### Data Cleaning:

Drop irrelevant or redundant columns (e.g., county, city, view_type).
Impute missing values for important features using median or most frequent values.
Convert ordinal features to numeric values for modeling.

![image](https://github.com/eva-vision/Real-Estate-Price-Predictions/assets/52841811/b14343da-a00b-4cc3-947c-7c9260c16868)


### Trend Analysis:

Fit a linear regression model to capture price trends over time.
Adjust the target variable to account for temporal trends.

![image](https://github.com/eva-vision/Real-Estate-Price-Predictions/assets/52841811/9766ce5f-613b-4147-84f6-6f677ce823b3)
![image](https://github.com/eva-vision/Real-Estate-Price-Predictions/assets/52841811/565be843-062a-4694-84bd-781ee918619c)


### Model Training and Evaluation:

Define feature sets and target variable.
Train multiple models (Linear Regression, Gradient Boosting Regressor, MLP Regressor) using cross-validation.
Evaluate models using metrics like RMSE, MAE, and MAPE.
Identify the best performing model and feature set based on evaluation metrics.

## Summary:

Document the best performing models and their feature sets.
Highlight potential areas for further improvement and additional analysis.
The primary goal of this code is to preprocess real estate data, create meaningful features, and build predictive models to estimate property prices accurately.
