# Project-3: Bank Marketing Analysis

## Overview
This project aims to analyze a bank marketing dataset to understand client behavior and predict whether clients will subscribe to a term deposit. The analysis includes data preprocessing, exploratory data analysis (EDA), and building predictive models using various machine learning algorithms.

## Table of Contents
- [Project Description](#project-description)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Data Preprocessing](#data-preprocessing)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Model Building](#model-building)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Project Description
The goal of this project is to analyze the bank marketing dataset to identify factors that influence a client's decision to subscribe to a term deposit. The project involves:
- Data cleaning and preprocessing
- Exploratory data analysis to visualize relationships
- Building and evaluating machine learning models

## Dataset
The dataset used in this project is sourced from the UCI Machine Learning Repository. It contains information about clients, including demographic details, account information, and previous marketing campaign results. The dataset can be found [here](https://archive.ics.uci.edu/ml/datasets/bank+marketing).

### Features
- `age`: Age of the client
- `job`: Type of job
- `marital`: Marital status
- `education`: Level of education
- `default`: Whether the client has credit in default
- `balance`: Client's bank balance
- `housing`: Whether the client has a housing loan
- `loan`: Whether the client has a personal loan
- `contact`: Type of communication
- `day`: Last contact day of the month
- `month`: Last contact month of the year
- `duration`: Duration of the last contact
- `campaign`: Number of contacts performed during this campaign
- `p`: Client's previous outcome
- `y`: Target variable (whether the client subscribed to a term deposit)

## Installation
To run this project, you need to have Python installed along with the following libraries:
- pandas
- numpy
- seaborn
- matplotlib
- scikit-learn

## Data Preprocessing
The data preprocessing steps include:

Handling missing values by treating 'unknown' as NaN
Encoding categorical features using Label Encoding and One-Hot Encoding
Scaling numeric features using StandardScaler
Splitting the dataset into training and testing sets
Exploratory Data Analysis
The EDA section includes visualizations to understand the distribution of client ages, bank balances, job types, and education levels, as well as their relationship with the target variable.

## Model Building
Various machine learning models are built and evaluated, including:

K-Nearest Neighbors (KNN)
Decision Tree Classifier
Logistic Regression
Support Vector Machine (SVM)

### Results
The performance of each model is evaluated using accuracy scores and classification reports. The results are compared to determine the best-performing model for predicting term deposit subscriptions.

#### Contributing
Contributions are welcome! If you have suggestions for improvements or want to add features, please fork the repository and submit a pull request.

#### License
This project is licensed under the MIT License. See the LICENSE file for details.
