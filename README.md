# Data Exploration on Melbourne Airbnb Market

Many people from regional areas want to be an Airbnb host after tourism revolution. These potential hosts and investors wonder know the room price setting and factors that affect room price.

There was total 17,751 observations recording 74 features in Melbourne Airbnb market from 2009 to present, which I obtained from the insightsairbnb website. 

Questions were below, 
Q1. Why price was higher in some part of Melbourne? 
Q2. Why some room type asked for higher price? 
Q3. How Airbnb price has been changed by year and region?
Q4. What was relationship between host number and price?
Q5. Need we pay more for the Airbnb room owned by a super host?

Challenges were below,
1. Outlier definition.
2. Present data to people who were not familiar with Melbourne.
3. Better model performance.

I used Python pandas to clean data, including filling missing value by median price or frequency value or reference data, format converting and outlier definition. Then applying geopandas and seaborn packages to overview price distribution and the relations between price and regions, years, host and room types respectively which were good way to help understanding the Airbnb development trace even did not know Melbourne areas. Finally after label encoding, data scaling, feature importance and hyperparameter tuning,  I built a model by random forest regression by sklearn package.

...

In the end. The important factors that affecting Airbnb room price like region, year, room type and host were presented by sorts of graphs. But the model performance was a little overfitting. Even I only research one scope, maybe model tried hard to find patterns in training data that were just caused by random chance, I need more time to deeply looked at the training dataset and testing dataset considering about covariate shift problems and label encoding problems. And I also would like to do text analysis about find the pattern between room price and review in the future.

