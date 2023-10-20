# Project-SECOM_Process_Success_Prediction

## Table of Contents

1. [Project Overview](#project-overview)
2. [Data Loading and Preprocessing](#data-loading-and-preprocessing)
3. [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
4. [Resampling](#resampling)
5. [Model Training and Evaluation](#model-training-and-evaluation)
6. [Results and Prediction Heatmap](#results-and-prediction-heatmap)
7. [Conclusion](#conclusion)
   
## Project Overview

Welcome to the Secom Semiconductor Company Data Prediction Project. This project's primary objective is to predict Success and Fail outcomes based on Secom Semiconductor Company's production data.

## Data Loading and Preprocessing
https://www.kaggle.com/datasets/paresh2047/uci-semcom

In the initial phase of the project, I meticulously loaded Secom's production data and conducted thorough data preprocessing. This step involved various data cleaning processes, including handling missing values and addressing outliers. Furthermore, I transformed categorical data into a numerical format through methods such as one-hot encoding and label encoding for enhanced analysis.

## Exploratory Data Analysis (EDA)

The heart of this project was the Exploratory Data Analysis (EDA) phase. My goal was to delve into the data's intricacies and understand its key characteristics. The primary EDA activities consisted of:
- Dealing the missing values
- Visualizing data distributions to detect potential outliers.
- Uncovering correlations between variables.
- Addressing class imbalance issues through informative visualizations.

## Resampling

To mitigate the challenges associated with class imbalance, I judiciously employed a combination of undersampling and oversampling techniques. This approach yielded a balanced class distribution and significantly improved the overall model performance.

## Model Training and Evaluation

My predictive model arsenal included the following machine learning algorithms:

- XGBoost
- Random Forest
- Logistic Regressor
- Lasso Regression

Each model underwent comprehensive training with the training dataset. The evaluation process incorporated cross-validation to ensure robust performance assessments. Evaluation metrics encompassed accuracy, precision, recall, F1 score, and the visual representation of ROC curves and AUC scores.

## Results and Prediction Heatmap

Following the rigorous model training and evaluation, the project culminated in the analysis of prediction results. These results were meticulously aggregated and presented in the form of an informative heatmap. This visualization allowed for a straightforward comparison of model performance, shedding light on the strengths and weaknesses of each approach.

## Conclusion

The Secom Semiconductor Company Data Prediction Project represents an exhaustive effort to predict Success and Fail outcomes using the available production data. The project's findings offer valuable insights into the performance of various machine learning models, contributing to potential improvements in Secom's production processes.

## Usage
1. Clone this repository:
git clone https://github.com/Junyoung0426/Project-SECOM_Process_Success_Prediction.git
2. Open the Jupyter Notebook:
jupyter notebook insurance_prediction.ipynb
3. Run the notebook to preprocess data, perform EDA, train models, and make predictions.

