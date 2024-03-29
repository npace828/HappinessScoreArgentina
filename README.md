# HappinessScoreArgentina
# Argentina Happiness Score vs GDP Linear Regression

## Overview
This project aims to analyze the relationship between the "Happiness Score" of Argentinians vs. the GDP
## Libraries Used
- **pandas**: Data manipulation and analysis
- **numpy**: Mathematical operations and array processing
- **seaborn**: Data visualization library based on matplotlib
- **matplotlib**: Plotting library for creating visualizations
- **scikit-learn**: Library for machine learning tasks
  - `train_test_split`: Splitting dataset into training and testing sets
  - `LinearRegression`: Linear regression model for predicting target variable
  - `OrdinalEncoder`, `OneHotEncoder`: Encoding categorical variables
  - `SimpleImputer`: Imputation strategy for handling missing values
- **category_encoders**: Library for encoding categorical variables
- **RandomForestClassifier**: Ensemble learning method for classification tasks

## Usage
1. Ensure all required libraries are installed. You can install missing libraries using pip
2. 2. Load the dataset containing the happiness score and GDP data for Argentina.
3. Preprocess the data as needed, including handling missing values and encoding categorical variables.
4. Split the dataset into training and testing sets using `train_test_split`.
5. Create a linear regression model using `LinearRegression`.
6. Fit the model to the training data.
7. Evaluate the model's performance using appropriate metrics.
8. Visualize the relationship between GDP and the happiness score using `seaborn` and `matplotlib`.
9. Draw conclusions based on the analysis.

## License
This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).

