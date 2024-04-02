# **Sentiment Analysis on Google Maps Review State University of Malang with XGBOOST with 2 Hyperparameter Tuning Methods (Grid Search CV & Randomized Search CV).**

## **Problem Statement**
- Is user sentiment towards UnState Univesity of Malang reflected in reviews on Google Maps?
- How effective is the Gradient Boosting model in analyzing the sentiment of user reviews of State University of Malang on Google Maps?
- What is the comparison of model performance from the two methods, namely gridsearch and randomsearch?

## **About This Project##
- in this project, i examined Hyperparameters tuning methods of ensamble learnning (XGBOOST).
- to see whether there is a difference between the 2 hyperparameter tuning methods

### **Workflows of the project:**
1. Data Scrapping: Using Chrome Extention (Instant Data Scraper)
2. Text Prepropcessing : case folding, normalized data, stopwords filtering, teknization and stemming.
3. Modelling: feature extraction, train test spli, k-fold cross validation, hyperparameter tuning (Grid Search CV & Randomized Search CV)
4. Evaluation: confusion matrix, accuracy, recal, precicion, f1-score, ROC Curve and AUC 
