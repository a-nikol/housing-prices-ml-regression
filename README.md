# Housing Prices Prediction using Machine Learning Regression

This repository contains Python code for predicting housing prices using machine learning regression techniques. The main steps include:

## Data Loading and Preprocessing:

- Importing the housing prices dataset.
- Handling missing values using custom imputation methods.
- Exploring the dataset and performing feature engineering if necessary.
- Encoding categorical variables for model compatibility.
- Normalizing the data using standard scaling.

## Exploratory Data Analysis (EDA):

- Visualizing data relationships using correlation matrices, pair plots, PCA, and t-SNE.
- Understanding feature distributions and their impact on the target variable.

## Model Training and Evaluation:

- Implementing various regression algorithms including Linear Regression, Decision Tree Regression, Random Forest Regression, and XGBoost Regression.
- Splitting the dataset into training and testing sets.
- Training each model and evaluating their performance using metrics such as Mean Squared Error (MSE), Mean Absolute Error (MAE), Mean Absolute Percentage Error (MAPE), and R-squared.
- Visualizing predictions on both training and test sets.

## Repository Structure

- **README.md**: Contains information about the project, dataset, methods, and results.
- **data**: Directory containing the dataset (median-price-dataset.csv).
- **housing-prices-ml-regression.ipynb**: Jupyter notebook containing Python code for data processing, EDA, model training, and evaluation.

## Instructions for Running the Code

1. Ensure you have Python installed on your system along with the necessary libraries specified in the notebook.
2. Download the dataset (median-price-dataset.csv) and place it in the `data` directory.
3. Open and run the `housing-prices-ml-regression.ipynb` notebook using Jupyter or any compatible environment.
3. Follow the instructions and execute the code cells sequentially to perform data processing, EDA, model training, and evaluation.

## Results Summary
- The project enhances prediction accuracy of housing prices by implementing various regression algorithms. Techniques such as feature engineering, including creating new features like 'rooms_per_household', and model retraining with feature selection contribute to improving prediction performance.
- Data preprocessing techniques such as handling missing values using fuzzy spatial extrapolation, feature scaling with StandardScaler, and dimensionality reduction using PCA and t-SNE prepare the data for analysis. Exploratory data analysis (EDA) techniques, including correlation analysis and visualization using seaborn and matplotlib, provide insights into housing market trends and influential factors affecting property prices.
- The project compares the performance of different regression algorithms, including Linear Regression, Decision Tree Regression, Random Forest Regression, and XGBoost Regression. Evaluation metrics such as Mean Squared Error (MSE), Mean Absolute Error (MAE), and R-squared are used to assess model performance and identify the most effective approach for predicting housing prices.

Achieving accurate housing price prediction provides a competitive advantage in the real estate market by offering better pricing estimates, enhancing customer satisfaction, and optimizing business operations.
