# Small Towns, Big Risks: Uncovering the Drug Overdose Outliers in America’s Noncore Counties
**By Tenzin Nepali** 
This is a final project completed for DATASCI 112: Principles of Data Science class at Stanford University

There was extensive research done in order to determine the predictors which are able to accuratly determine what defines a county in the U.S. to be suseptible to high drug overdose rates. I extracted data from the U.S. census API, CDC NCHS, and the US Customs and Border patrol to find different predictors and their correlations to death-rates based on the bayesian model. The bayesian model is a statisitcal method which shrinks data with smaller sample sizes, determined by their variability. This is used here to accuratly assess the death-rate model for rural/noncore county's. 

As a result of the study I found that: 
  1. The primary group affected by high drug rates are these hard to identify small communities
  2. Drug seizures do not allign with the model-death rate and are not correlated to County's having high model-death rates.
  3. Socioeconomic data is also a great predictor of county's which are at risk of high-overdose rates.
Additionally with this knowledge I was able to create a hypertuned model that predicted high-overdose risk county's at an accuracy of 79%. I hope that future studies can be conducted in order to predict high risk communities by looking at population and socioeconomic data, and work to reducing overdose rates nationally.

Here is the link to my analysis: https://github.com/Tengoku1/DataScienceProject/blob/main/Data_Science_Analysis.ipynb

Here is the link to my data exploration and graphs: https://github.com/Tengoku1/DataScienceProject/blob/main/Data_Science_Exploration.ipynb
