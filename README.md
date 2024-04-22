# Energy-Efficiency-Regression-Analysis-Project

This project aims to analyze the heating and cooling load requirements (energy efficiency) of buildings using various architectural parameters such as building shape, glazing area, orientation, and others. The analysis is performed using machine learning regression techniques on a dataset containing 768 samples and 8 features.

## Dataset

The dataset used in this project contains the following features:

- `X1`: Relative Compactness
- `X2`: Surface Area
- `X3`: Wall Area
- `X4`: Roof Area
- `X5`: Overall Height
- `X6`: Orientation
- `X7`: Glazing Area
- `X8`: Glazing Area Distribution

The target variables are:

- `y1`: Heating Load
- `y2`: Cooling Load

The goal is to use the eight features to predict each of the two target variables (heating and cooling load) using regression models.

## Methodology

The project employs various machine learning regression techniques, including:

1. **Linear Regression**: A baseline model to establish a performance benchmark.
2. **Polynomial Regression**: A non-linear regression model to capture complex relationships between features and target variables.
3. **Decision Tree Regression**: A tree-based model that can naturally handle non-linear relationships and feature interactions.
4. **Random Forest Regression**: An ensemble method that combines multiple decision trees to improve predictive performance and reduce overfitting.

The project also includes data preprocessing steps, such as handling missing values, scaling features, and transforming skewed features to improve model performance.

## Requirements

To run this project, you'll need the following dependencies:

- Python (version 3.6 or higher)
- NumPy
- Pandas
- Matplotlib
- Seaborn
- SciPy
- Scikit-learn

## Code Analysis

The code follows a structured approach to data analysis and model building. It includes the following main steps:

1. **Data Loading and Exploration**: The dataset is loaded, and exploratory data analysis is performed to understand the characteristics of the features and target variables.
2. **Data Preprocessing**: Missing values are handled, skewed features are transformed, and features are scaled to improve model performance.
3. **Feature Selection**: Irrelevant or weakly correlated features are removed to reduce dimensionality and improve model efficiency.
4. **Model Training and Evaluation**: Multiple regression models are trained and evaluated using various performance metrics, such as R-squared, mean absolute error, and mean squared error.
5. **Hyperparameter Tuning**: Grid Search Cross-Validation is used to find the optimal hyperparameters for Decision Tree Regression and Random Forest Regression models.

## Conclusion

This project provides a comprehensive analysis of building energy efficiency using architectural parameters. By employing different regression techniques and carefully preprocessing the data, the models can accurately predict heating and cooling loads for various building designs. The Random Forest Regression model consistently outperforms other models, demonstrating its robustness in handling non-linear relationships and feature interactions.

## Contributing

Contributions to this project are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.
