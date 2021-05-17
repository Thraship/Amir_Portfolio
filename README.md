*Amir's Data Science Portfolio*

# [Project 1: Stroke Prediction](https://github.com/Thraship/stroke_prediction) 
![brain stroke](/images/brain2.png)

## Motivation
The endgoal for this project is to answer the following questions:

1. Could a relatively accurate model be developed for predicting stroke probability?
2. What are the most important factors in predicting the above probability?

## Project Overview
- The objective is to predict the likelihood of patients getting strokes based on input features such as age, gender, bmi, ...
- Dataset was attained from https://www.kaggle.com/fedesoriano/stroke-prediction-dataset
- Cleaned data from over 5000 patients
- Created and optimized a Random Forest Classification model by using GridSearchCV to reach 94.4% accuracy to predict stroke probability
- Model was saved using joblib library


# [Project 2: Data Science Salary Prediction](https://github.com/amirostad/Web_scraping_jobs) 
![data science salary](/plots/project_pic.png)

## Motivation
The endgoal for this project is to answer the following questions:

1. Can a data scientist role's earnings be estimated?
2. What features are important in predicting a data scientist's earnings?

## Project Overview
- The objective is to predict the salary of data scientist positions based on location, seniority, type of the company, industry, etc.
- The dataset used in this project is a combination of dataset obtained from https://www.kaggle.com/andrewmvd/data-scientist-jobs and extra data scientist positions scraped by glassdoor scraper uploaded to this repository
- Cleaned dataset of over 5500 data scientist positions
- Created and optimized Random Forest Regression model by using GridSearchCV to reach MAE=0.29, RMSE=2.26, and R<sup>2</sup>score=0.99
- Model was saved using joblib library
