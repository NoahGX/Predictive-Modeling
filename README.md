# Predicitve Modeling and Clustering

## Overview
The purpose of this Jupyter Notebook is to employ various machine learning techniques that analyze and predict data outcomes. Each project is focused on a different dataset: the Titanic dataset for survival prediction, California housing data for price prediction, and Wine quality data for clustering.

## Features
- **Titanic Survival Prediction**: Uses logistic regression to predict survival based on passenger data.
- **California Housing Price Prediction**: Applies regression analysis to forecast housing prices.
- **Wine Quality Clustering**: Implements K-means clustering to group wines based on quality metrics.

## Usage
- Open the notebook in a Jupyter environment.
- Ensure all prerequisites are installed.
- Run the cells sequentially to load the data, preprocess it, perform exploratory data analysis (EDA), build models, and visualize results.

## Prerequisites
- Python 3.x
- Libraries: pandas, numpy, matplotlib, seaborn, sklearn
- Jupyter Notebook or JupyterLab

## Input
- Titanic dataset: Accessed from an online repository via a URL.
- California housing data: Loaded using sklearn's `fetch_california_housing` function.
- Wine quality data: Loaded using sklearn's `datasets.load_wine()` function, which provides the dataset pre-packaged within the library.

## Output
- Predictive models for Titanic survival and California housing prices.
- Cluster analysis for wine quality.
- Visualizations for exploratory data analysis and results interpretation.

## Notes
- Ensure that all datasets are accessible and that the paths or URLs provided are correct.
- Adjust hyperparameters as necessary based on specific data characteristics or desired accuracy.