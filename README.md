
# Exploring Titanic Dataset: Data Cleaning, Feature Engineering and Analysis


This repository contains an in-depth analysis of the Titanic dataset, exploring various aspects of the passengers' information and their survival outcomes. The project involves data cleaning, feature engineering and data visualization to gain insights into factors influencing survival of passengers on the Titanic.

## Project Overview

The Titanic dataset analysis is organized into several stages:

1. **Data Loading:** The dataset containing passenger information is loaded using Python's pandas library. It includes information about passengers' attributes such as age, sex, class, fare, etc.

2. **Data Exploration and Visualization:** Exploratory data analysis is conducted to understand the distribution of different variables and their relationships with survival. Visualizations such as bar plots, histograms, box plots, and heatmaps are created using libraries like seaborn and matplotlib.

3. **Data Cleaning:** Missing values in columns are imputed using appropriate strategies. Outliers may be handled using techniques like winsorization. Redundant columns might be dropped to streamline the analysis.

4. **Feature Engineering:** New features are created from existing ones to extract useful information. For example, titles are extracted from passengers' names, age and fare are categorized, and family size is calculated.

5. **Categorical Variable Encoding:** Categorical variables are encoded using one-hot encoding to convert them into a format suitable for machine learning algorithms.

6. **Correlation Analysis:** The correlation between different variables is calculated and visualized using a heatmap to identify relationships between features.


## Dependencies

The project requires the following dependencies:

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scipy
- Jupyter Notebook (for interactive exploration)


