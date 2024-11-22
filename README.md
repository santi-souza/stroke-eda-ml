# Stroke: Prediction of risk analysis based on machine learning, exploratory data analysis (EDA) and statistical analysis.

## Overview

This repository contains a comprehensive analysis of stroke prediction using the [Stroke Prediction Dataset](https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset). The analysis includes exploratory data analysis (EDA), statistical testing, and machine learning predictions. The work is implemented in R, with RMarkdown for documentation and Flexdashboard for interactive visualization and insights. View it [here](https://santisouza.shinyapps.io/DashboardTFM/)

A simple visualization on how it looks: 

![dash3](https://github.com/user-attachments/assets/261abf9a-ae03-4d9e-a39b-599b58a312a5)

## Key Features

- **Data Preprocessing:** 
    - Handling missing values (NA) through imputation
    - Renaming columns for clarity, removing redundant columns, and organizing data into categorical and numerical variables
    - Converting categorical variables to factors for analysis

- **Exploratory Data Analysis (EDA):** 
    - Visualizations and statistical summaries to understand variable distributions and relationships

- **Statistical Testing:** 
    - Evaluation of associations between variables using appropriate statistical tests

- **Machine Learning Models implementation and assessment of:** 
    - Random Forest
    - Logistic Regression
    - Gradient Boosting

- **Interactive Dashboard:** 
    - A Flexdashboard for interactive data exploration and visualization. [View Dashboard Here](https://santisouza.shinyapps.io/DashboardTFM/).

## Contents

- `TESIS.Rmd`  
  Main RMarkdown file with the full analysis, including data preprocessing, EDA, statistical tests, and model evaluations.

- `DashboardTFM.Rmd`  
  RMarkdown file that generates the Flexdashboard, providing an interactive interface for data exploration.

- `stroke.csv`  
  Dataset used for analysis. You can also download it from [Kaggle](https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset) if needed.

## Setup and Usage

To run the analysis or explore the dashboard locally:

1. **Clone this repository:**

bash
git clone https://github.com/santi-souza/stroke-eda-ml.git

2. **Open the files:**

Open TESIS.Rmd or DashboardTFM.Rmd in RStudio to view the analysis or render the Flexdashboard.

## Analysis Highlights

1. **Data Preprocessing:**

Addressed missing values with imputation, clarified column names, removed unnecessary columns, and separated data into categorical (converted to factors) and numerical variables.

2. **Exploratory Data Analysis (EDA):**

Generated visualizations and statistical summaries to identify trends and patterns in the data.

3. **Statistical Testing:**

Performed hypothesis testing to assess relationships between various features and stroke occurrence.

4. **Machine Learning:**

Built and evaluated predictive models to identify key stroke risk factors.

5. **Interactive Dashboard:**

Developed an interactive Flexdashboard to enable users to explore the data and model results.

## Contributing

Contributions are welcome! If you’d like to suggest improvements or find any issues, feel free to open an issue or submit a pull request.
