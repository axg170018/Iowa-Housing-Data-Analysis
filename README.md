# Iowa-Housing-Data-Analysis
The goal of this project is to build a model that can help real estate agents predict the sales price for each house in Ames, Iowa. The data consist of 2,919 residential property sales in Ames, Iowa between 2006 and 2012 (1,460 in the training set).
# Frame the problem
Before looking at the data it is important to understand how does the company expect to use and benefit from this model? This first brainstorming helps to determine how to frame the problem, what algorithms to select and measure the performance of each one
# We can categorize our Machine Learning (ML) system as:
## Supervised Learning task: we are given labeled training data (e.g. we already know some of the sale price, for some houses);
Regression task: our algorithm is expected to predict the sale price for a given product and store.
Plain batch learning: since there is no continuous flow of data coming into our system, there is no particular need to adjust to changing data rapidly, and the data is small enough to fit in memory, so plain batch learning should work.

# Make Assumptions
We can make other assumptions about some predictors that might influence the fluctuation on the housing sale price:
Neighbourhood;
Year it was built;
Number of rooms;
Has a fireplace?
Has heating?
Has a pool?
Number of parking spots;
The lot size;
Proximity to schools, public transportations, malls, etc;
Type of dwelling;
Size of inside and outside areas.

# Organisation of our analysis
Our goal as a Data Scientist is to identify the most important variables and to define the best regression model for predicting the housing prices in Ames, Iowa. This analysis will be divided into four stages:
Exploratory data analysis (EDA);
Data Pre-processing;
Feature engineering;
Modeling and Hyperparameter tuning
