# SAAS Final Project: Predicting Global Economic Crises

This repository contains the code for my **Student Association of Applied Statistics (SAAS)** final project at UC Berkeley. The goal of the project was to develop predictive models capable of forecasting global economic crises based on a variety of economic indicators.

## Project Overview

We focused on using predictive modeling techniques to analyze historical economic data and predict the likelihood of global economic crises. We tested a variety of different models and conducted EDA and parameter fine-tuning to find the model with the best accuracy 

### Key Highlights
- **Dataset**: Utilized a dataset consisting of economic indicators from multiple countries over many decades. Sourced from https://www.hbs.edu/behavioral-finance-and-financial-stability/data/Pages/global.aspx. We exported this data to Excel, and we reformatted and cleaned the data in our Colab notebook. 
  
- **Models Used**:
  - Decision Trees
  - Logistic Regression
    
- **Data Preprocessing**:
  - Handled class imbalance using **SMOTE (Synthetic Minority Oversampling Technique)**.
  - Performed feature selection and engineering to enhance model performance.
- **Best Performing Model**: Decision Trees with SMOTE yielded the best accuracy among all models tested.

## Repository Contents

- **`SAAS_FINAL_Project.ipynb`**: Jupyter Notebook containing all the code for the project, from EDA to modeling
- **`README.md`**: This file, summarizing and outlining the project



