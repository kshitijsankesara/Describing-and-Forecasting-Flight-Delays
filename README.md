# Describing-and-Forecasting-Flight-Delays
We did a project on Describing and Forecasting Flight Delays using Microsoft Excel for our MBC 638 - Data Analysis and Decision Making coursework.
For this project, we analyzed the 2015 US Flights data set to uncover deep insights and to explain and predict flight delays.
We collected multiple data sets from Kaggle (https://www.kaggle.com/usdot/flight-delays)

Pre-Processing Data:
Merged Airlines, Airports, and Flights data set. The entire data consisted of 6 million rows and 35 columns.
Cleaned and transformed data extensively. Extracted Chicago Airport data and we kept that as our origin airport.
Retrieved Chicago’s weather data from the National Oceanic and Atmospheric Administration.
The weather data was very noisy and it had a lot of missing values. We cleaned the data and merged some of the weather data with our data using Vlookup.
Using domain knowledge and statistical techniques, we selected and used some key variables that impact our analysis the most.
Some of the qualitative data were transformed using different methods like dummy variables.

Descriptive Analysis:
Performed descriptive analysis to understand trends from past data.
Using descriptive statistics, we answered business questions like:
1. How many flights per airline are there in the data? 
2. How many flights per scheduled destination are there in the data? 
3. How many flights per scheduled destination are there in the data? 

Then we used different visualizations to answer important questions using different parameters: 
1. Which airlines typically have significant flight delays? 
2. Which scheduled destination airports typically have significant flight delays? 
3. Which time of year, month, and day have the most flight delays? 
4. Which flight distance range(s) show(s) the largest number of flight delays? 
5. What are the most common delay reasons? 
6. What are the top cancellation reasons? 
7. What was the weather data information by month? 

We build a 3D Map depicting delay routes and airlines.

TIME-SERIES MODEL:
We also build a Time Series Forecasting model to show seasonalities, monthly and yearly delays, and predict future delays.

REGRESSION:
We used Regression analysis to discover good predictors of flight delays.
We understood the relationship between quantitative variables by conducting Correlation Analysis.
We perform Feature Engineering on our data after knowing the significant factors of delays.
We used Logistic Regression, Simple Linear Regression, and Multiple Linear Regression using different subsets of our data to understand the predictors of flight delays.

Logistic Regression:
To understand how the data would affect the probability of getting delayed through the coefficients, and if the explanatory variables are good predictors for the Classification task.
After analyzing our model and updating it, we achieved an R-value of 0.997.

Simple Linear Regression:
To predict arrival delays using departure delays.
We build a scatter plot to analyze both the variables.
We obtained a correlation coefficient value of 0.94 for our model.

Multiple Linear Regression:
To predict arrival delays using Stepwise Multiple Linear Regression.
To understand how weather, airlines, destination airports, scheduled time of day, day of the week, etc. all affect arrival delays and if they are good predictors using Stepwise Regression.

Results & Conclusion:
We were successful in finding variables that significantly affected flight delays.
We got a very high correlation coefficient for our regression models, so the variables were found to greatly affect flight delays.
