### NBA Playoff Finalist Predictor in R
This repository contains an R notebook that showcases a predictive model for forecasting NBA playoff finalists. The model utilizes historical player statistics to make predictions for the Eastern and Western Conference finalists in the years 2020 and 2021.

#### Overview
Data Source:
 The code retrieves player statistics data from Basketball-Reference for the years 2015 to 2021, encompassing both basic and advanced statistics.

#### Data Processing: 
Player statistics are processed to remove unnecessary columns and ensure data consistency. Players with the most starts for each team are selected and data is scaled for modeling.

#### Feature Selection:
 Various multiple regression models with different subsets of features are explored to identify the most influential factors in predicting win shares (WS).

#### Model Evaluation: 
Models are evaluated using R-squared to measure predictive performance, determining the best-performing model.

#### Playoff Predictions: 
The selected model is used to predict win shares for players in 2020 and 2021. Predicted wins are aggregated by team to estimate total wins in the Eastern and Western Conferences.

#### Usage
You can use this code as a template to predict NBA playoff finalists for different years or customize features for prediction. Ensure you have the required R packages installed, including tidyverse, rvest, leaps, caret, corrplot, and dplyr.

#### Repository Structure
#### R Notebook:
Contains the complete R code for data collection, preprocessing, modeling, and predictions.
#### Requirements
Before running the code, make sure to install the necessary R packages: tidyverse, rvest, leaps, caret, corrplot, and dplyr.

