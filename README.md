# News-popularity-Prediction
Repository for my final semester of Data Science project with IITB, Bengaluru.

Dataset available: https://archive.ics.uci.edu/ml/datasets/Online+News+Popularity# 

# Problem Statement
Build a Regression models which accurately predict the popularity of new articles (the number of times it will be shared online) based on ~60 features provided.

# Importance online news popularity prediction
Online news popularity prediction includes gaining better insights into the audience consuming online news content. Consequently, it increases the ability of news organizations to deliver more relevant and appealing content in a proactive manner. Also, the company can allocate resources more wisely to prepare stories over its life cycle. Moreover, prediction of news content is also beneﬁcial for trend forecasting, understanding the collective human behavior, advertisers to propose more proﬁtable monetization techniques, and readers to ﬁlter huge amounts of information quickly and efﬁciently.

# Objective
To build an efficient ML model which could predict the number of shares of a specific news article before its publishing. This predictive model which you will build will serve the following purposes:
- It will be used to predict the number of shares a particular news article will receive based on its internal features before the publication. The model should be able to predict the article shares as closely as possible to the original shares.

- It will be used to identify which factors contribute most to the number of shares. These factors are essentially the attributes used in the dataset which were used in model building.

# Approach in nutshell
- 1. Data Understanding, preparation and pre-processing
- 2. Data Cleaning
- 3. EDA Analysis
- 4. Outliers Treatment
- 5. Feature Scaling
- 6. Checking Correlations
- 7. Model Building (Feature Selection Using RFE, PCAImprovising the model further inspecting adjusted R-squared, VIF and p-vales)

### Checking null values using missingno library
![image](https://user-images.githubusercontent.com/76435558/153936296-66ab22d6-606c-400a-a861-45ad9f1c29a3.png)

# Data Science Model
Our goal was to find the best fit model for our dataset. We incrementally fitted models to our data set which included models like Linear Regression, Ridge Regression, Lasso Regression.

# Model Evaluation:
We used RMSE, R2 and Mean absolute error to make it more accurate.

# Results:
We used Ridge Regression for prediction as it has lowest RMSE.

Tech
----------------------------------------
The following technologies were used for this part of the project:
- Python 3
- Jupyter Notebook
- Pandas: Python package for data analysis
- Numpy: Python package for numerical analysis
- Scikit-learn: Python package for predictive analysis
- Matplotlib, Seaborn and Missingno: Python 2D plotting library

