# Fantasy Premier League Analytics

This project applies machine learning techniques to predict the positions of Premier League football players based on their performance statistics. Using data from the 2019/2020 season, we explore, preprocess, and apply various machine learning models to make our predictions. The ultimate goal is to provide a tool that can help in sports analytics, team management, fantasy football decisions, and sports betting insights.

## Table of Contents

- [Project Overview](#project-overview)
- [Data Description](#data-description)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Modeling](#modeling)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)

## Project Overview

The project workflow is as follows:

1. **Data Loading and Cleaning**: Load the dataset, set appropriate column names, and perform initial cleaning.
2. **Exploratory Data Analysis (EDA)**: Perform initial analysis to understand the dataset better through visualizations and statistics.
3. **Data Preprocessing**: Filter data to include only relevant players, based on playing time, to ensure model relevance.
4. **Model Selection and Training**: Evaluate and train multiple machine learning models to predict player positions.
5. **Model Evaluation**: Use a validation set to evaluate model performance, using accuracy and other metrics.
6. **Feature Importance Analysis**: Analyze which features are most influential in predicting player positions.
7. **Application to Latest Season**: Apply the model to the latest season's data to predict player positions.
8. **Results and Insights**: Analyze and present the results, focusing on the accuracy of position predictions and identifying key players.

## Data Description

The dataset includes detailed performance metrics for Premier League players in the 2019/2020 season, such as:

- Minutes Played
- Goals Scored
- Assists
- Clean Sheets
- Penalties Saved/Missed
- Yellow/Red Cards
- Player Influence, Creativity, and Threat Metrics

## Exploratory Data Analysis (EDA)

We use histograms, box plots, and scatter matrices to understand the distribution and relationship between various performance metrics. This step is crucial for identifying patterns and outliers in the data.

## Modeling

We evaluate several machine learning models:

- Logistic Regression
- Linear Discriminant Analysis (LDA)
- K-Nearest Neighbors (KNN)
- Decision Tree Classifier
- Gaussian Naive Bayes
- Support Vector Machines (SVM)

The models are trained on the dataset, and their performance is compared to select the best one for our prediction task.

## Usage

To run the analysis and model training, follow these steps in the `Football_Fantasy_ML.ipynb` Jupyter Notebook:

```bash
# Clone the repository
git clone <repository-url>

# Navigate to the project directory
cd <project-directory>

# Install dependencies
pip install -r requirements.txt

# Run the Jupyter Notebook
jupyter notebook Football_Fantasy_ML.ipynb
```

Follow the notebook instructions to load the data, perform EDA, train the models, and evaluate their performance.

## Results

The project includes a detailed comparison of model performances and an analysis of feature importance. The best model is then applied to the latest season's data to predict player positions, and the results are analyzed to provide insights into player performance and model accuracy.

## Contributing

Contributions are welcome! If you have suggestions for improving the model or extending the project, please feel free to fork the repository and submit a pull request.

