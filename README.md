# Analyzing the Kaggle Titanic Spaceship Dataset

![Titanic](https://storage.googleapis.com/kaggle-competitions/kaggle/23080/logos/header.png)

This repository provides an analysis of the Kaggle Spaceship Titanic competition dataset. The aim of this dataset is to predict whether passengers on the Titanic spaceship were transported to another dimension based on various features.

## Project Overview

The project includes the following components:

Data Exploration and Feature Engineering: The Numpy and Pandas libraries are utilized to explore and manipulate the dataset. Furthermore, mlxtend is used to implement Sequential Forward Floating, a wrapper method, for assisting in feature engineering

Data Visualization: Using the powerful Python library Plotly, create interactive charts for data exploration. Compared to other libraries, it is more helpful in intuitively understanding the data and visualizing the appearances of different features.

Machine Learning: The machine learning aspect involves utilizing scikit-learn, XGBoost, and LightGBM libraries to build predictive models. These models are trained on the dataset to predict whether a passenger was transported to another dimension.

After comparing and adjusting hyperparameters using the grid search method, the LightGBM model was selected to build the predictive model. The final accuracy reached 80.5%.

### The versions of libraries used are as follows:  

Python: 3.10.12
Numpy: 1.25.2
Pandas: 1.5.3
Plotly: 5.16.1
Mlxtend: 0.22.0
scikit-learn: 1.2.2
XGBoost: 1.7.6
LightGBM: 4.0.0

## Credits

Credits to Kaggle for providing the dataset and platform for the competition.

