# LR_Thrillers
Linear Regression for Thriller Movies

# Client / Background
This was my first experience creating a linear regression machine learning model as part of the Metis curriculum. This project also required webscraping which was another first for me. 

The mock business situation that I created for my project: There's a newly created production studio that plans to make movies in the thriller genre. They'd like to know which characteristics of thrillers are predictors of US box office gross.

# Business Questions
- Does a set of features do a good job in predicting US Gross for thrillers?
- Which features are significant predictors of US Gross for thrillers?

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
- Correlation matrix (Determined features with most viability based on correlation to target)
- Reg Plots, R^2
- Addressed colinearity issues
- Feature Engineering
#### Determine Baseline Model 
- Tested log transform vs no transform
- Determined if regularization would improve the model
- Identified features with highest coefficient
#### Train - Validate - Test
- Utilized cross validation

# Findings
Check out the presentation [here](https://github.com/Jenni-Hawk/LR_Thrillers/blob/main/Presentation_Linear_Regression.pdf)

# Tech Tools Used
- Request Module, BeautifulSoup Library
- Pandas
- Seaborn
- Statsmodels
- CPI Library (to apply inflation to budget based on year)
- Sklearn

