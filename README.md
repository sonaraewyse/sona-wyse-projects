# SAAS Projects: Predicting Economic Crises and Forecasting Chemical Levels in Water

This repository contains the code used in my projects for the Student Association of Applied Statistics (SAAS) at UC Berkeley. My **first project** was on developing predictive models capable of forecasting **global economic crises** based on a variety of economic indicators. My **second project** was a part of the consulting work we provided for the Environmental Protection Agency. Our goal was to **forecast levels of specific chemicals** in water wells across California to improve regulatory practices and protect drinking water. 

## Project 1 Overview

We focused on using predictive modeling techniques to analyze historical economic data and predict the likelihood of global economic crises. We tested a variety of different models and conducted EDA and parameter fine-tuning to find the model with the best accuracy 

### Key Highlights
- **Dataset**: Utilized a dataset consisting of economic indicators from multiple countries over many decades. Sourced from https://www.hbs.edu/behavioral-finance-and-financial-stability/data/Pages/global.aspx. We exported this data to Excel, and we reformatted and cleaned the data in our Colab notebook. 
  
- **Models Used**:
  - Decision Trees
  - Logistic Regression
    
- **Data processing**:
  - Handled class imbalance using **SMOTE (Synthetic Minority Oversampling Technique)**.
  - Performed feature selection and engineering to enhance model performance.
- **Best Performing Model**: Decision Trees with SMOTE yielded the best accuracy among all models tested.

## Project 2 Overview

My role in the project was conducting time series analysis and forecasting with Meta's Prophet procedures. The team we worked with at the Environmental Protection Agency wanted insights on levels of the top 5 most prevalent chemicals across water wells in California. While I was able to build models forecasting levels of certain chemicals, the data was not comprehensive enough for my models to make accurate predictions. Sampling was *too irregular, and there was no continuity across time. Further, there were too many unpredictable events and too little data for certain areas in California.*  


### Key Highlights
- **Dataset**: Utilized a dataset on chemical levels in water wells throughout California, provided to us by the team at the EPA. 
  
- **Models Used**:
  - Time Series Forecasting models taking into account seasonality, trends, linear or logistic growth
    
- **Data processing**:
  - Filtered for top 5 chemicals
  - Tested aggregating chemical levels by the mean
  - Investigated relationship of chemical levels over time
  - Performed parameter fine-tuning of Prophet models

## Repository Contents

- **`SAAS_FINAL_Project.ipynb`**: Jupyter Notebook containing all the code for the **economic crisis project**, from EDA to modeling
- **`EPA Time Series Forecasting.ipynb`**: Jupyter Notebook containing code used for time series analysis and forecasting on **chemical levels**
- **`README.md`**: This file, summarizing and outlining the project



