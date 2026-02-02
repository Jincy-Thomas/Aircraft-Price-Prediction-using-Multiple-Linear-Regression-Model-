# ✈️ Aircraft Price Prediction

## Overview
This project builds a predictive model to estimate aircraft prices using technical and performance specifications such as engine power, speed, range, and wingspan.  
Using regression modeling and statistical model selection, we identify the key drivers of aircraft pricing and develop an accurate price prediction model.

## Dataset
- 518 aircraft records  
- 14 numerical + 2 categorical features  
- Target: price (USD)  
- Source: Kaggle – Aircraft Price Analysis & Prediction  

## Methods
- Data cleaning & preprocessing
- Exploratory data analysis and visualization
- Multicollinearity check (VIF)
- Model selection (Forward, Backward, Stepwise, All-subsets)
- Interaction & higher-order regression models
- Residual diagnostics and assumption testing

## Results
- Final model Adjusted R²: **0.9248**
- Residual Standard Error: **$279,400**
- Explains ~**92% of price variability**

### Key predictors
- Engine type
- Engine power
- Cruise speed (nonlinear effect)
- Stall speed
- Wing span
- Interaction terms

## Tech Stack
- R / RStudio
- Linear Regression
- Statistical Modeling
- Data Visualization
