# SAAS Projects: Predicting Economic Crises and Forecasting Chemical Levels in Water

This repository contains the code used in my projects for the **Student Association of Applied Statistics (SAAS)** at UC Berkeley. My first project was on developing predictive models capable of forecasting global economic crises based on a variety of economic indicators. My second project was a part of the consulting work we provided for the Environmental Protection Agency. Our goal was to forecast levels of specific chemicals in water wells across California to improve regulatory practices and protect drinking water. 

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


## Repository Contents

- **`SAAS_FINAL_Project.ipynb`**: Jupyter Notebook containing all the code for the project, from EDA to modeling
- **`README.md`**: This file, summarizing and outlining the project



