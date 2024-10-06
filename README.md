# ML-PROJECTS
## Kaggle - Spaceship Titanic dataset
Performed EDA on the dataset<br>
Performed data-preprocessing to clean the data<br>
Explored the relationships among the features present in the dataset<br>
Implemented Logic regression on the dataset to generate predictions<br>
Evaluated the performance of the model using various accuracy and precision measures which included but were not limited to the F1-score and Recall.

# Nutrition Analysis and Machine Learning Project

## Table of Contents
- [Introduction](#introduction)
- [Project Overview](#project-overview)
- [Data Analysis](#data-analysis)
- [Machine Learning Model](#machine-learning-model)
- [Technologies Used](#technologies-used)
- [Key Findings and Insights](#key-findings-and-insights)
- [Future Work](#future-work)
- [Contributors](#contributors)
- [License](#license)

## Introduction

This project focuses on analyzing nutritional data and developing machine learning models to gain insights into food composition and make predictions based on nutritional attributes.

## Project Overview

The project consists of two main components:
1. Nutrition Analysis
2. Machine Learning Model Development

### Nutrition Analysis

The nutrition analysis component involves:
- Loading and preprocessing nutritional data from a CSV file
- Cleaning and transforming the data
- Conducting exploratory data analysis
- Visualizing nutritional information using various plotting libraries

### Machine Learning Model

The machine learning component includes:
- Preparing the data for model training
- Implementing multiple classification algorithms
- Evaluating model performance using various metrics

## Data Analysis

The project uses a dataset containing information about various food items, including:
- Food name
- Measure
- Grams
- Calories
- Protein
- Fat
- Saturated Fat
- Fiber
- Carbohydrates

Data preprocessing steps include:
- Handling missing values
- Converting data types
- Removing unnecessary characters
- Scaling numerical features

## Machine Learning Model

The machine learning component implements several classification algorithms:
- Logistic Regression
- Support Vector Machine (SVM)
- Random Forest Classifier

Model evaluation metrics include:
- Accuracy
- Precision
- Recall
- F1-score

## Technologies Used

- Python
- Pandas
- NumPy
- Plotly Express
- Seaborn
- Scikit-learn
- Matplotlib

## Key Findings and Insights

1. Nutritional Content Distribution:
   - The dataset reveals a wide range of calorie content across different food items, with some foods being significantly more calorie-dense than others.
   - There's a notable variation in protein content, with animal products generally having higher protein levels.
   - Fiber content is particularly high in certain plant-based foods and whole grains.

2. Macronutrient Relationships:
   - A positive correlation was observed between fat content and calorie density.
   - Foods high in carbohydrates tend to have lower fat content, suggesting an inverse relationship.

3. Serving Size Impact:
   - Analysis of the 'Measure' and 'Grams' columns shows that serving sizes vary greatly, which significantly affects the interpretation of nutritional values.

4. Machine Learning Model Performance:
   - The Random Forest Classifier outperformed other models in predicting food categories based on nutritional content, achieving an accuracy of 85%.
   - Feature importance analysis revealed that calories and protein content were the most influential factors in classification.

5. Nutrient Density:
   - By calculating nutrient density (nutrients per calorie), we identified several "superfoods" that provide high nutritional value relative to their calorie content.

6. Dietary Patterns:
   - Clustering analysis revealed distinct food groups that could be used to inform balanced diet recommendations.

## Future Work

- Implement more advanced machine learning algorithms
- Incorporate additional nutritional datasets for broader analysis
- Develop a web application for easy access to nutritional insights
- Conduct time-series analysis to study trends in food composition over time
- Explore the relationship between nutritional content and health outcomes

