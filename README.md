# Classification Modelling for Income Prediction
This project focuses on analyzing income data and building classification models to predict whether an individual's income exceeds $50,000 annually. The dataset used for this analysis includes various demographic and financial features such as age, race, sex, occupation, workclass, country and relationship status.
The following models have been used:
    + Naive Bayes
    + Knn
    + Decision Tree
    + Random Forest
# Installation and Setup
## Resources
1. Editor: Jupyter Notebook
2. Python version: Python 3.11.9
3. Python Packages used: 
    + General Purpose: io
    + Data Manipulation: pandas, numpy
    + Data Visualization: matplotlib, seaborn
    + Machine Learning: scikit, imblearn
## Data
+ Data Acquisition
The source data is a csv file 'income.csv' which can be accessed [here](https://drive.google.com/file/d/1Al7zqgGUwACT4Bp32CtiG3NiJtDMfIGR/view?usp=drive_link)
+ Data Preprocessing
The dataset contains a few missing/unknown values which have been represented with the '?' symbol.
We have replaced this with nan values using numpy.
The column headers may also have an extra space when loaded into a dataframe.
## Results and Evaluation
The random forest model achieved the highest accuracy, precision, recall and F1 score. The decision tree classifier had almost a similar score as knn with the knn model being only slightly higher. The Naive bayes classifier had the lowest in all four metrics used.



