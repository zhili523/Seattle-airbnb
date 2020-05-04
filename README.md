# Motivation
This project is following the requirement of Data Scientist Nanodegree of Udacity to share my data understanding on GitHub and Medium.
I pick the Seattle Airbnb open dataset from Kaggle, seeking to provide some insight of Seattle Airbnb market for who are potential visitors to Seattle or local hosts in Seattle.

In this project, I will answer six bussiness related questions on Seattle Airbnb market, from both potential visitor and local host perspectives:

From Visitor view:

1. How does the price of Airbnb fluctuate across a year in Seattle?
2. *How are the available listing and rent price distributed by location in Seattle?
3. *Will the experience of Seattle Airbnb renters vary by time?

From Airbnb providers view:

1. When is the peak and off-peak season?
2. *What can host do to improve their review rating score?
3. *For whoever is considering becoming an Airbnb host in Seattle, how competitive are they in this market by comparing with other experienced hosts?

([Medium post](https://medium.com/@wenzhili523/airbnb-market-in-seattle-a-closer-look-from-the-perspectives-of-host-and-visitor-89b179cde17) only cover four questions with * marked for better representation)

# Required Libaries
1. This project was written by Python, using Jupyter Notebook, including common packages: pandas, numpy, matplotlib, seaborn, calendar, datetime, sklearn.
2. To analyze the text of comment, it is necessary to install vaderSentiment and detectEnglish.
3. To enable the associations function to analyze the correlation between categorical and continuous variables, you will need to install dython package.

# The Description of Files
1. seattle_airbnb.ipynb — dataset includes the written code for data analysis
2. calendar.csv — dataset includes availability and price of listings from 2016/01/04 to 2017/01/02
3. listings.csv — dataset includes each listings informations, such as location, price, number of reviews and so on
4. reviews.csv — dataset includes over 80k reviews written by guests between 2009 and 2016
5. detectEnglish.py — used to detect if a string is English, provide by http://inventwithpython.com/hacking (BSD Licensed)
6. dictionary.txt — A dictionary file of English words, one per line, to enable the function of detectEnglish.py

# Summary

For visitors:

If you are traveling to Seattle, the majority of Airbnb options are located in central and northern Seattle. 
Northern Seattle has the best balance—being price friendly and having many stay options to choose from. 
Pick travel time according to your own schedule, you are likely to have same experience with your Airbnb homeowner, 
no matter during peak season or off-peak season. 
But keep in mind, the renting price is much higher during peak season (July, August, September), especially on Friday or Saturday of the week.

For local hosts:

Usually July, August, and September will be the peak tourist season in Seattle, and less visitors will come on December, January, and February.
To become a highly-rated host, timely communication with your guest is very important.
If you are considering to becoming an Airbnb host in Seattle, 
you will be able to earn your own place in the market if you can out-perform other newbie hosts that open business the same year.

# Credit and Reference

1.	[A Complete Exploratory Data Analysis and Visualization for Text Data - Susan Li](https://towardsdatascience.com/a-complete-exploratory-data-analysis-and-visualization-for-text-data-29fb1b96fb6a)
2.	[The Search for Categorical Correlation – Shaked Zychlinski](https://towardsdatascience.com/the-search-for-categorical-correlation-a1cf7f1888c9)
3.	[Data Visualization of Uber Rides with Tableau – Vanessa Leung](https://towardsdatascience.com/data-visualization-of-uber-rides-with-tableau-67988f61f712)
