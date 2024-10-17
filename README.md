# Stats-Project

# Asylum Data Analysis and Prediction

This repository contains a comprehensive analysis and prediction project focused on asylum seekers' demographics. Using various machine learning algorithms, the project aims to predict the number of asylum seekers based on their demographic information over the years.

## Table of Contents
- [Introduction](#introduction)
- [Datasets](#datasets)
- [Data Cleaning](#data-cleaning)
- [Feature Engineering](#feature-engineering)
- [Modeling](#modeling)
- [Visualization](#visualization)
- [Requirements](#requirements)
- [Usage](#usage)

## Introduction
The goal of this project is to analyze the demographics of asylum seekers and predict future trends using machine learning techniques. The focus is on understanding the factors influencing asylum applications and how they change over time.

## Datasets
The project utilizes three main datasets:
1. **`demographics.csv`**: Contains demographic information of asylum seekers, including age and gender distributions.

## Data Cleaning
Data cleaning is performed to ensure the quality of the datasets before analysis. The following steps are undertaken:
- **Handling Missing Values**: Null values in critical columns, such as `Location Name`, are dropped. For numeric columns, median values are used to fill missing entries.
- **Data Type Conversion**: Relevant columns are converted to the appropriate data types (e.g., integers, floats).
- **Dropping Unnecessary Columns**: Columns that do not contribute to the analysis are removed to streamline the dataset.

## Feature Engineering
- The data is prepared for modeling by defining independent variables (X) and the dependent variable (y).
- Standardization is applied to the features to improve model performance.
- Train Test Split is carried out using the scikit-learn libraries

## Modeling
The following machine learning models are utilized:
- **Multiple Linear Regression**
- **Decision Tree Regressor**
- **Random Forest Regressor**
- **XGBoost Regressor**

## Visualization
Visualizations are created using `matplotlib` and `seaborn` to explore correlations between features and identify patterns in the data. A heatmap of correlations is included, along with scatter plots for feature relationships.

## Requirements
To run this project, make sure to install the required libraries:
1. Create a conda environment:
   ```bash
   conda create --name <name_of_the_environment> python=<desired_python_version>
   ```
2. Activate the environment
   ```bash
   conda activate <name_of_the_environment>
   ```
3. Install the requirements using requirements.txt file
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Clone the repository: 
```
git clone https://github.com/Parth0124/Stats-Project.git
```
