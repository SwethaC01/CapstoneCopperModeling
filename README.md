# CapstoneProject_IndustrialCopperModeling

## Project Overview
This project involves understanding and preprocessing data,EDA and developing machine learning models to address challenges in the copper industry related to sales, pricing, and lead capturing. Specifically, the project focuses on building a regression model to predict the selling price and a classification model to predict the status (WON/LOST) of leads. Additionally, an interactive Streamlit web application will be created to facilitate real-time predictions using these models.

## Domain: 🏭Manufacturing

## 🛠 Technologies Used
* Python
* Numpy
* Pandas
* Scikit-learn
* Matplotlib
* Seaborn
* Pickle
* Streamlit

## 📘 Approach

### Data Understanding:
Load and understand the copper data through CSV files.
Check the data for consistency and completeness.
### Data Preprocessing:
Loaded the copper CSV into a DataFrame.
Cleaned and filled missing values, addressed outliers,and adjusted data types.
Analyzed data distribution and treated skewness.
### Exploratory Data Analysis(EDA):
Understanding and visualizing the data using EDA techniques such as boxplots, histograms, and scatter plots.
### Feature Engineering:
Drop highly correlated columns using a heatmap from Seaborn.
### Model Evaluation through Regression and Classification Model:
Split the dataset into training and testing sets.
Train and evaluate regression models for 'Selling_Price'.
Train and evaluate classification models for 'Status'(WON/LOST).
Pickled the trained models for deployment.
### Streamlit:
The user interface and visualization are created using the Streamlit framework.

### 💻 Import Packages and Libraries
```python
import pandas as pd
import numpy as np
import seaborn as sns
import matplotlib.pyplot as plt
from streamlit_option_menu import option_menu
import pickle
import streamlit as st

pip install scikit-learn 
pip install xgboost 
pip install streamlit 
pip install pickle
pip install scipy
pip install imblearn
