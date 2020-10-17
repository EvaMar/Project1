# What Seattle and Boston AIRBNB Data can tell us

## Intro
Number of Data available is increasing each day. This allowes data scientist to discover correlations that could not be revealed only few years ago.  
AIRBNB is an example of available data source that could help investigate what are the most imporant factors for a property rent and what are the most expensive area.  
The purpose of this analysis is to show the tip of the iceberg of what data science can do, such as:  
 - The most expensive neighbourhoods in Boston and Seattle  
 - Can a Machine Learning Alghoritm help predicting the renting price of a property?
 - what are the most important factors which can affect the price?

## Installation
To view the results of the analysis no installation is necessary. Simply open the Jupyter Notebook NDProject1 in this repository.  
To replica the analysis, make sure you have the necessary python packages:
 - numpy
 - pandas
 - sklearn.linear_model
 - sklearn.model_selection
 - sklearn.metrics

## Seattle and Boston AIRBNB Data
Data are available in this repository. They can also be downloaded in:  
https://www.kaggle.com/airbnb/seattle/data  
https://www.kaggle.com/airbnb/boston

## Results
At the end of analysis - which can be found in the job repository - the following results have been found:  
 - On average, Seattle top 5 neighbourhoods are more expensive than Boston no. 1: Southeast Magnolia, which can only compare to Seattle no 6: Chinatown
 - Machine Learning can predict a property renting price. Linear Regression returned a r2 score of 0.546 which increased to 0.555 after an easy adjustment to the parameter. Further investigation (for example a difference choise of model) can increase the r2 score even further
 - Room type and neighbourhood are, unsurprinsigly, the most important factors. However, it is interesting to see than the number of bathrooms has a similar importance than the 
 host acceptance rate and the request of guest phone verification. While the number of bedrooms is of, course, quite significant, the actual number of beds isn't. 
 The fact that the host is a super host is also relevant. It is also interesting to notice that the fact the host provides a profile picture seems to negatively influencing the price. Even the request for the guest to have a profile picture seems to give the same effect.
Feature that may seems importance such as instant booking, reviews, host response time, etc. do not seem to have a great impact on the price

## Creator
Eva Marchetti

## Thanks
Udacity Data Science Nano Degree
![alt text](https://github.com/[username]/[reponame]/blob/[branch]/image.jpg?raw=true)
