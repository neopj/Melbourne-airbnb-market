# Melbourne-Airbnb-Market

People expect tourism recovery after Covid border restrictions becoming history. When visitors’ numbers scale up as before, Airbnb will be one of the hot careers against a routine work. For those willing to be an Airbnb host or a professional host, how to set price is definitely a priority. 

There was total 17,751 observations recording 74 features in Melbourne Airbnb market from 2009 to present, which I obtained from the insightsairbnb website. My aim was to figure out which factors affect Airbnb price and what is their relationship. And training a model to predict the price and recognize the important factors.

Questions were below,
Q1. Why price was higher in some part of Melbourne?
Q2. Why some room type asked for higher price?
Q3. How Airbnb price has been changed by year and region?
Q4. What was relationship between host number and price?
Q5. Need we pay more for the Airbnb room owned by a super host?

I used Python pandas to preprocess csv.gz source files, including fill missing value by median price or frequency value or reasonable value, also has done format converted and outlier definition. Then applying geopandas and seaborn packages to overview price distribution and the relations between price and regions, years, host and room types respectively. Finally training a model and further understood the top importance factors affecting price by sklearn package.

I overviewed the distribution of Airbnb price over four dimensions including region, year, room type, and host via different forms of charts. All those Airbnb were less than $910.28/night. In addition, I used maps to show the evolution of Airbnb over time, so that Melbourne residents and investors who are unfamiliar with Melbourne can better understand the factors that affect Airbnb prices. 

After deep analysis, I chose 10 features out of 74 total features to train a model for predicting Airbnb price which were less than $400/night.  And 91% variance in Airbnb room price can be explained by the features I chose through the model. But the model is a bit overfitting, I will better it in the future research.
