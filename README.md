# Problematic Internet Use Prediction 📡
This repository contains our solution for the Problematic Internet Use Prediction competition hosted by Kaggle in collaboration with the Child Mind Institute. The competition aims to predict problematic internet use among adolescents using behavioral, psychological, and demographic data.

## Overview
Problematic internet use is a growing concern, particularly among adolescents. This competition provides an opportunity to leverage machine learning to identify individuals at risk based on provided datasets. Our goal is to create a robust predictive model that can aid in early intervention and prevention strategies.
Data is provided by Healthy Brain Network (HBN) with ~5000 children aged 5-22 years participating in clinical and research screening.
Our Objective is Predict Severity Impairment Index (sii) - internet usage level, based on physical activity data and internet usage behavior, sii is integer between 0 and 3


## Features
📊 Data Analysis: Comprehensive exploratory data analysis (EDA) to uncover trends and patterns.
🧠 Feature Engineering: Advanced techniques to optimize dataset quality and performance.
🤖 Model Development: Use of cutting-edge machine learning models including ensemble methods.
📈 Evaluation: Robust metrics to evaluate model performance and ensure accuracy.
## Dataset
The dataset is provided by Kaggle and includes anonymized behavioral, psychological, and demographic attributes.

## Key Files:

train.csv: Training dataset with labeled outcomes.
test.csv: Test dataset for predictions.
sample_submission.csv: Template for final submission.
Target Variable:

sii: Internet usage level, based on physical activity data and internet usage behavior
Note: Access the dataset via the competition page: Kaggle Competition Link

## Installation
Follow the steps below to set up the project on your local machine:

Clone the repository:
bash
git clone https://github.com/LaRojaPlamya162/MachineLearning_ChildMindInsitute.git

## Technologies Used
Programming Language: Python
Libraries:
pandas
numpy
matplotlib
seaborn
os
concurrent.futures
sklearn (experimental, impute, model_selection, metrics)
scipy (optimize)
xgboost
lightgbm
tqdm
sklearn (ensemble, preprocessing)
plotly.graph_objects
IPython.display

## Tools:
Jupyter Notebook
Project Structure

## Evaluation
The model is evaluated by Quadratic Weighted Kappa (QWK) - a performance metric designed to compare predicted and actual labels, especially for problems with ordinal labels. The QWK value ranges from -1 to 1

## Results
Best Model: Voting Ensemble combining LightGBM, Random Forest Regressor and XGBOOST

## Contact
Author: ML Teams 
Members: 
Trần thái An 22028210
Nguyễn Tuấn Anh 22028310
đào đình hiếu 22028221
Kaggle Profile: https://www.kaggle.com/tuannguy
GitHub: LaRojaPlamya162
Feel free to open an issue or reach out with any questions!
