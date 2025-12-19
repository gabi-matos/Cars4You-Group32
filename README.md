# Cars4You-Group32
Machine Learning project predicting car prices.

This repository contains the Machine Learning group project developed for the Machine Learning course. 

The project addresses a business problem of **Cars4You**, an online car resale company, with the goal of improving and accelerating the car price evaluation process using machine learning techniques. 

---

## Project Context

Cars 4 You currently requires each car to go a mechanical inspection before assigning a purchase price. Due to company growth, the waiting times increased, leading to potential customer loss.

The objective of this project is to develop a predictive model capable of estimating car prices using only the information provided by users at the time of registration, without requiring a prior mechanical inspection.

--- 

## Objectives

The project is structured around 3 main goals:

1. **Regression Benchmarking**  
   Develop and compare multiple regression models to accurately predict car prices.

2. **Model Optimization**  
   Improve model performance through feature engineering, preprocessing, and hyperparameter tuning, selecting the most generalizable solution.

3. **Open-Ended Extension**  
   Implement a classification model that segments cars into **Low, Medium, and High price categories**, to, then implement our Regression Model to the specific category the car belongs to.

---

## Dataset

Two datasets are provided:
- **Training set** (with price labels)
- **Test set** (without price labels)

Only features realistically available at the time of user input were used. 'PaintQuality%' was, therefore, removed since it relies on a mechanic assessment.

---

## Methodology

### Preprocessing & Feature Engineering
- Data cleaning
- Incoherencies checking
- Data spliting - features/ target & train/ validation 
- Outliers treatment
- Missing values treatment
- Feature engineering
- Scalling
- Encoding 

### Models Implemented
- Linear Regression
- Decision Trees
- Random Forest
- Neural Networks (MLP)
- Ensemble (Bagging, Staking, Boosting, Blending)

### Evaluation
- **Regression**: Mean Absolute Error (MAE)
- **Classification**: Accuracy

Hyperparameter optimization was performed using **RandomizedSearchCV**.

--- 

## Authors

Group 32 - Carlota Magalhães; Gabriela Matos; Mariana Carvalhais 





