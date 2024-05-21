# Phase 3 Data Science Salaries Predictions
Author: Ruth Nyakio

## Overview
Classification of Data Scientists Salary data to predict compensation based on :
* Cost of living in different locations
* Size of the company can mean more revenue and higher budget for salaries
* Experience levels affect compensation
* Employment Type
* Remote, hybrid or in person agreements

## Business Problem
With the harsh employment climate in Kenya, more Kenyans are seeking for jobs abroad specifically in the US either remote or in person. However, job seekers rely on fragmented salaries information. This can lead to inaccurate estimates for which can cause job seekers to undervalue themselves or employers to overpay. Moringa school has Career Services Office that provides career coaching, essential skills, and business connections to help students achieve their professional goals. As part of their project to support Data Science students, Moringa has tasked Hepta Analytics to develop a predict analytics to assist Moringa students in making informed decisions about compensation while looking for jobs Abroad specifically in the US.

## Data
* This project utilizes data from https://ai-jobs.net/salaries/form/ and https://www.kaggle.com/datasets/arnabchaki/data-science-salaries-2023 AI jobs collects salary information anonymously from data science professionals and employers worldwide collected from 2020 and 2024.
* The target variable from this dataset is the salaries
* 11 Unique Features
* There were 18,737 Salaries

## Methods
* Data cleaning: Handling duplicates, missing, null values  and encoding categorical variables
* Data visualization: Heatmaps, Histograms, Tableau, scatter plots
* Data Preparation: Feature selection , Encoding and Scaling and Class Imbalance handling
* Modeling: Logistic regression, Random Forests, and Decision Trees
* Model Valuation & Improvement : Classification Report, Cross-Validation, Hyperparameter Tuning
   
## Results
* Salary distribution

* Salary vs work year and Salary vs remote ratio

* Salary vs company type and Salary vs Employment Type
  
* Logistic Regression Model Results
  

## Conclusions
* Performance:
  * Logistic Regression: 39.77% accuracy
  * Random Forest: 39.60% accuracy
  * Decision Tree: 32.31% accuracy

## Recommendations
* Add more features:: Age, Company's Revenue, Skills, Year of Experience etc.
* Try Ensemble Methods:  Bagging (e.g., Random Forest) or Gradient Boosting) 
* Do Feature Transformation: Log transformations to normalize data 
* Feature Selection: Choose best features that improve our predictive model


## Next Steps
* Data Enrichment
* More Feature Engineering
* Salary (Target) Re-grouping
* More Hyperparameter Tuning
* Try more Models such as SVM

## Links to project resources
* Presentation - 
* Code - 
* Data Source - 

## Repository Structure
<img width="332" alt="image" src="https://github.com/ruth-karimi/Real-Estate-Renovations/assets/24277899/f59c8eb3-42e1-472c-a6d0-25912326997e">
