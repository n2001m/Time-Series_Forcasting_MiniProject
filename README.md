# Traffic Volume Prediction Project

## Overview

This repository contains a Jupyter notebook for a traffic volume prediction project. The project uses time series data of vehicle traffic at different junctions to build and compare various deep learning models for predicting future traffic volumes.

## Project Description

The notebook demonstrates the following key steps:

1. Data Loading and Preprocessing:
   - Loads traffic data from a CSV file and a MongoDB database
   - Performs initial exploratory data analysis (EDA) using libraries like skimpy and summarytools

2. Feature Engineering:
   - Extracts temporal features from the datetime column (hour, day of week, month, year)

3. Data Visualization:
   - Uses seaborn and plotly to create various plots for understanding traffic patterns

4. Model Building and Evaluation:
   - Implements three different deep learning models:
     - Long Short-Term Memory (LSTM)
     - Gated Recurrent Unit (GRU)
     - Convolutional 1D - GRU hybrid
   - Uses TensorFlow and Keras for model implementation
   - Evaluates models using mean squared error (MSE) and plots actual vs predicted values

5. Model Saving:
   - Saves trained models for future use

The project showcases skills in data preprocessing, time series analysis, deep learning model implementation, and data visualization using Python and various data science libraries.
