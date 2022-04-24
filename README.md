# Can we predict Happiness?
Contributed by 

- [@jinruiiii](https://github.com/jinruiiii)

- [@Tan Yu](https://github.com/Tan-Yu)

- [@Jlorj](https://github.com/Jlorj)

## About
Hi there! Welcome to our mini Data Science project for SC1015 (Introduction to Data Science and Artificial Intelligence)!
In this project, we will be exploring some of the factors that can be used to predict a happiness score. 
Each of the following source codes contains the data cleaning, analyses, visualisations, and model predictions based on these 2 factors that we have selected to investigate.

1. [CO2 Emissions Per Capita](https://github.com/Jlorj/SC1015_MiniProject/blob/main/HappinessAndCO2.ipynb)
2. [Internet Users by Percentage](https://github.com/Jlorj/SC1015_MiniProject/blob/main/HappinessAndInternet.ipynb)

## Problem Statement
- Happiness in the world is in jeopardy.
- Based on a selection of factors, are we able to predict a happiness score?

## Initial Hypothesis
- Lower levels will make people happier because the Climate Change is getting better!
- High internet usage will make people happier as they have more access to entertainment and freedom of speech.

## Model Used
- Linear Regression

## Limitations Faced 
- Initial dataset for Cantril Ladder was too small if we took 1 year's worth of data as only 166 countries partakes in the Cantrill Ladder poll every year. Instead, we combined data across 15 years to capture more data points.

- Isolation Forest technique in detecting anomalies requires a good estimation of the contamination value to remove anomalies effectively. 

- Current world data on internet usage is limited - dataset contains too many NaN values for several countries, which may lead to over-estimation of the happiness index of the country.

## Concluding Remarks and Learning Points
- Utilised a new technique Isolation Forest to remove anomalies effectively from the dataset.
- The higher the CO2 emissions, the higher the Cantril Ladder Score (a.k.a. Happiness).
- The higher the Internet Usage, the higher the Cantril Ladder Score (a.k.a. Happiness).
- Internet Usage is a better predictor than CO2 emissions per capita in predicting the Cantril Ladder Score.
- CO2 emissions may not necessarily be a bad predictor in predicting the Cantril Ladder Score.

## Contributions
Jin Rui - Isolation Forest, Data Extraction and Visualisation

Tan Yu  - Data Cleaning and Refinement of Exploratory Data Analysis

Joel    - Evaluation of Machine Learning Model Results 

## References
- Our World in Data. (2017, May). *Happiness and Life Satisfaction.*

   https://ourworldindata.org/happiness-and-life-satisfaction
   
- Our World in Data. (2020, August). *CO₂ and Greenhouse Gas Emissions.*

   https://ourworldindata.org/co2-and-other-greenhouse-gas-emissions

- The World Bank. (n.d.) *Individuals using the Internet (% of population).*

   https://data.worldbank.org/indicator/IT.NET.USER.ZS
- Analytics Vidhya. (2021, July 26). *Anomaly detection using Isolation Forest – A Complete Guide.*

   https://www.analyticsvidhya.com/blog/2021/07/anomaly-detection-using-isolation-forest-a-complete-guide/
- scikitlearn. (n.d.). *sklearn.ensemble.IsolationForest.* 

   https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.IsolationForest.html
- Mulvaney, K. (2022, February 28). *Climate change already worse than expected, says new UN report. National Geographic.*

   https://www.nationalgeographic.com/environment/article/climate-change-already-worse-than-expected-un-report
- Africa will continue to suffer coups and civil wars in 2022. (2021, November 8). *The Economist.* 

   https://www.economist.com/the-world-ahead/2021/11/08/africa-will-continue-to-suffer-coups-and-civil-wars-in-2022
- How COVID-19 affects mental health. (2020, May 18). *Singapore Institute for Clinical Sciences (SICS).*

   https://www.a-star.edu.sg/sics/news-views/blog/blog/covid-19/angst-and-anger-why-does-the-covid-19-pandemic-make-us-so-upset
- TRADING ECONOMICS. (2022, March 10). *United States Inflation Rate - March 2022 Data - 1914–2021 Historical - April Forecast.*

   https://tradingeconomics.com/united-states/inflation-cpi#:%7E:text=US%20Inflation%20Rate%20Hits%20New,of%201982%2C%20matching%20market%20expectations.


