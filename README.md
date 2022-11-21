# Learn Fundamentals of Linear Regression + Machine Learning
- Viability Analysis
- Instantiate Model, Train + Test, Score
- Statsmodels and Sklearn

# Client / Background
This was my first experience creating a linear regression machine learning model as part of the Metis curriculum. This project also required webscraping which was another first for me. 

The mock business situation that I created for my project: A newly emerged production studio plans to make movies in the thriller genre and would like to know which characteristics of thrillers are predictors of US Box Office Gross.

# Business Questions
- Does a set of features do a good job in predicting US Gross for thrillers?
- Which features are significant predictors of US Gross for thrillers?
- Check out the [presentation](https://github.com/Jenni-Hawk/Linear_Regression/blob/main/Linear_Regression_Preso.pdf)

# Data to Answer the Question
- IMDB List of Thrillers for target and feature data
- 1100 thriller titles, 16 predictor variables

# Solution Path
#### Webscraping
- Scraped 1100 of the top grossing thriller titles, 16 predictor variables
#### Exploratory Data Analysis
- Ensure data correct and appears as expected
- Data cleanup, address missing values, etc
#### Regression Viability
- Correlation matrix (Determined features based on correlation to target)
- Reg Plots, R^2
- Addressed colinearity issues
- Feature Engineering
#### Instantiate Model
- Train + Test
- Get Predictions
- Identified features with highest coefficient

# Findings
Check out the presentation [here](https://github.com/Jenni-Hawk/Linear_Regression/blob/main/Linear_Regression_Preso.pdf)

# Tech Tools Used
- Request Module, BeautifulSoup Library
- Pandas
- Seaborn
- Statsmodels
- CPI Library (to apply inflation to budget based on year)
- Sklearn

