# Electrical Grid Stability Data Mining Project

This repository contains a data mining and machine learning project focused on analyzing and predicting the stability of an electrical grid system.

The project uses the **Electrical Grid Stability Simulated Data Set** from the UCI Machine Learning Repository. The dataset represents a decentralized smart grid system and includes features related to reaction time, power production/consumption, price elasticity, and grid stability.

## Project Overview

The stability of electrical grids is an important issue in modern energy systems, especially with the increasing use of decentralized and renewable energy sources. This project applies data mining and machine learning techniques to analyze the factors affecting grid stability.

This project includes both:

* **Classification**: Predicting whether the grid is stable or unstable
* **Regression**: Predicting the numerical stability value of the grid

## Objectives

The main objectives of this project are:

* To explore and understand the Electrical Grid Stability dataset
* To analyze the relationship between input features and grid stability
* To preprocess the dataset for machine learning models
* To perform feature selection and feature transformation
* To classify the grid condition as stable or unstable
* To predict the numerical stability value using regression models
* To train and compare different classification and regression models
* To evaluate model performance using appropriate metrics
* To identify the most effective models for grid stability prediction

## Dataset Description

The dataset contains simulated data for a 4-node electrical grid system.

The main feature groups are:

* `tau1` to `tau4`: Reaction time of each node
* `p1` to `p4`: Power production or consumption
* `g1` to `g4`: Price elasticity or willingness to adapt
* `stab`: Numerical stability value used for regression
* `stabf`: Categorical stability label used for classification

The dataset contains:

```text
10,000 observations
14 columns
```

## Target Variables

This project uses two target variables:

```text
stab
```

`stab` is a numerical variable that represents the grid stability value. It is used for regression tasks.

```text
stabf
```

`stabf` is a categorical variable that classifies the grid condition as:

```text
stable
unstable
```

It is used for classification tasks.

## Project Workflow

The project follows these main steps:

1. Importing required libraries
2. Loading and exploring the dataset
3. Checking data information, missing values, skewness, kurtosis, correlation, and covariance
4. Performing data visualization and exploratory data analysis
5. Encoding the categorical target variable
6. Detecting and removing outliers
7. Performing feature selection
8. Comparing models with and without selected features
9. Applying feature transformation techniques
10. Training and evaluating classification models
11. Training and evaluating regression models
12. Performing hyperparameter tuning
13. Comparing final model performances

## Exploratory Data Analysis

The notebook includes several exploratory analysis steps, such as:

* Dataset shape and data types
* Missing value analysis
* Statistical summary
* Skewness and kurtosis analysis
* Correlation matrix
* Covariance matrix
* Heatmaps
* Distribution plots
* Boxplots
* Pair plots
* Feature relationship visualizations

## Classification Models

Several classification models are trained and evaluated to predict whether the grid is stable or unstable.

The classification models include:

* Logistic Regression
* K-Nearest Neighbors
* Decision Tree
* Random Forest
* Support Vector Machine
* XGBoost
* LightGBM
* CatBoost
* TabNet Classifier
* Neural-network-based classification models

## Regression Models

Regression models are also used to predict the numerical stability value of the grid.

The regression models include:

* Linear Regression
* Support Vector Regression
* Gradient Boosting Regressor
* CatBoost Regressor
* LightGBM Regressor
* TabNet Regressor
* Neural-network-based regression models

## Model Evaluation

Classification models are evaluated using:

* Accuracy
* Precision
* Recall
* F1-score
* Confusion matrix
* Classification report
* ROC curve
* AUC score

Regression models are evaluated using:

* Mean Absolute Error
* Mean Squared Error
* Root Mean Squared Error
* R-squared score

## Feature Engineering

The project includes feature selection and feature transformation experiments.

Feature selection is performed using:

* Correlation analysis
* Random Forest feature importance

Feature transformation methods include:

* StandardScaler
* RobustScaler
* Log transformation
* Exponential transformation
* Box-Cox transformation

## Results

The project compares different machine learning models for both classification and regression tasks.

For classification, the goal is to accurately predict whether the grid condition is stable or unstable.

For regression, the goal is to predict the numerical stability value of the electrical grid.

The results show that advanced machine learning models such as Support Vector Machine, Random Forest, XGBoost, LightGBM, and CatBoost can provide strong performance for grid stability prediction.

## Project Structure

```text
electrical-grid-stability-data-mining/
│
├── electrical_grid_stability_analysis.ipynb
├── Data_for_UCI_named.csv
├── requirements.txt
└── README.md
```

## Requirements

This project requires Python 3.

Required Python packages are listed in:

```text
requirements.txt
```

You can install them using:

```bash
pip install -r requirements.txt
```

## How to Run

1. Clone or download this repository.
2. Install the required packages.
3. Open the Jupyter Notebook:

```bash
jupyter notebook electrical_grid_stability_analysis.ipynb
```

4. Run the notebook cells step by step.

## Dataset Source

The dataset used in this project is the Electrical Grid Stability Simulated Data Set from the UCI Machine Learning Repository.

## Author

Reza Darabpour

## License

This project is provided for educational and data mining practice purposes.
