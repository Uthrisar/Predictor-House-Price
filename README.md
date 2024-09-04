# House Price Prediction

## Overview

This project focuses on predicting house prices using two widely-used machine learning techniques: **Linear Regression** and **Gradient Boosting Regressor**. By analyzing various features of houses—such as the number of bedrooms, square footage, location, and more—we aim to build models capable of estimating house prices with reasonable accuracy. This project is especially valuable for real estate professionals, homebuyers, and anyone interested in understanding the factors influencing property prices.

## Project Structure

- **data/**: Contains the dataset used for training and testing the models.
- **notebooks/**: Includes Jupyter notebooks used during the exploratory data analysis (EDA) and model training processes.
- **models/**: Stores the saved models after training.
- **scripts/**: Holds Python scripts for data preprocessing, model training, and evaluation.
- **README.md**: This file provides an overview of the project.

## Dataset

The dataset used in this project includes various features that are commonly associated with house prices. These features may include:

- Number of bedrooms
- Number of bathrooms
- Square footage of the house
- Location (city, neighborhood)
- Age of the house
- Proximity to amenities (schools, parks, etc.)
- And more...

## Methods Used

### 1. Linear Regression
Linear Regression is a simple and interpretable model that assumes a linear relationship between the features and the target variable (house price). It serves as a good baseline model to compare the performance of more complex models.

### 2. Gradient Boosting Regressor
Gradient Boosting is an ensemble technique that builds models sequentially, with each new model attempting to correct the errors made by the previous models. The Gradient Boosting Regressor generally provides better accuracy than linear models, especially in cases with complex relationships between features.

## Setup

To run this project, you will need Python installed along with the following packages:

- `pandas`
- `numpy`
- `scikit-learn`
- `matplotlib`
- `seaborn`

You can install the required packages using the following command:

```bash
pip install -r requirements.txt
