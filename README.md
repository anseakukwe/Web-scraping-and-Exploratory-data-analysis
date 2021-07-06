# Web-scraping-and-Exploratory-data-analysis
This is a project on web scraping and exploratory data analysis in Python

Overview 

This case study was don exclusively in the Python programming language.

The following steps were realized to complete the task.

The Guardian Media Group API is a public web service for accessing all the content the Guardian creates, categorized by tags and section. 
To get started, you need a key to successfully authenticate against the API.

There are two types of keys namely Developer and Commercial. For This Task, I made use of the Developer API Key.
In order to use the Developer API, I signed up for it, and a key was sent to my email address.

The next step was to extract the all the data from 01.01.2018 until today. 
A quick check discovered that the Developer API key only allows 200 search contents per page. 
However, the number of contents for Justin Trudeau for the search period of 01.01.2018 were more than 850. 
As such the search contents for Justin Trudeau were splitted into Quarters of Yearly Period, to accommodate this limitation from the Guradian Developer API. 
This means that data were extracted in portions, and later concatenated to form one single data frame for data analysis.

Exploratory data analysis was performed on the data, to answer questions from the task.

Data visualization was performed using the interactive data visualization library Plotly. 
The choice of this library over the matplotlib of Python, which is because of it's interactive capabilities.
