#info

STAT-361_Linear Models

#Final_Project : Statistical Analysis of Insurance Coverage Against Social Status
#Authors : Kevil Khadka, Jialin Xiang, Rafael Pereira
#dataset : civil_rights.csv

#Abstract
This study works on a dataset which includes the information about the insurance companies
which were denying the insurance coverage for the certain number of people (miniority) 
living within geographical areas. This project focuses on relationship between the minority 
and denial of coverage. More specifically,we look certain explanatory variables to find out 
if there are any reasons why people living within certain areas have to take governemnt issued 
insurance policy instead of private insurance. The purpose of the analysis is to find out the 
ethical reason to see if there was any discriminiation upon minority people from private insurance companies. 
We build a mulitple linear regression model that helps to explain if the variables like fires, thefts and minor 
have any influence on the being denied from the insurance companies.
We found that there is pretty good linear relationship between the percentage of population 
as minority and government issued policies. Also we discovered that the private companies were discriminiating 
the minority people by denying their insurance policies.

#Introduction
Do the private insurance companies look at all people's applications equally when deciding whether
to provide coverage? Are they illegaly canceling the applications based on the applicant's background 
and history of their residence area?

Nearly a decade after the black civil righs movement in the United States (1954 - 1968), investigations 
were conducted to look into reports of health care denials to certain people. The information collected 
after the commission's inspections resulted in 47 observations of different geographical areas of Chicago, Illinois,
which provided some interesting insights. Based on the zipcode provided on the dataset, it was found that miniority 
people were residing in Chicago area. Today, 50 years later, after some data analysis and some data cleaning,
multiple linear regression models can be created to demonsrate that discrimination did exist against minorities in
the late 1970s. It seems that insurance companies were actually denying coverage for certain people. On this data analysis 
report, we want to create a simple model that could answer our questions of interest, which are listed below: 

(1) Is there evidence of a relationship between race and the denial of coverage?
(2) Can that relationship be explain away by the insurance companies? 
(3) Did the insurance companies illegally discriminate against minorities?

This study will look the most accuarate model to answer our questions by using various data anaylsis method, 
checking any influential outliers, refining the model, and selection techniques.

#Dataset
The data set we used to study our question had eight variables (two categorical, and six quantitative), 
and 47 rows of data representing geographical areas of the state of Illinois. It provided the number of 
government-offered policies that were issued broken down by ZIP Code. Those people who were denied by private 
insurance coverage received the government-issued policies provided by the government.Though, to build the best
model and make a good prediction for our question, we might have to fix some of our data. The reason for this is
the presence of aggregated points in our observations. 

These are the eight variables we worked with:

Zip : ZIP Code of area;
Minor : Percentage of population as minority;
Fires : Number of fires per 100 houses;
Thefts : Number of thefts per 1000 people;
Const : Percentage of houses constructed before 1939;
Plan : New government-issued policies and renewals per 100 houses;
Income : Median income for family (thousands of dollars);
Location : Location of house (north or south side of city).
