#### DSI18 Capstone Project
### Analysing of UK Traffic Accidents 2005-2015
## Background
Over the last twenty years, the streets have begun to become increasingly crowded n the latest statistics, a total of 1,752 people were killed in reported road traffic accidents in Great Britain.The quantity and severity of the accidents, plus the adverse effects of traffic congestion can not be ignored.
To identify the features of those Hotspots depending on a relevant dataset and investigate the best way to classify the data depending on different features, such as: morning peak hours, night off-peak and weekends) to reduce accident risk.
## Goals
This is where we can use data science magic to tell us something we didn’t know about our data.
In this project, relying on the main causes of car accidents in 10 years helped answer some questions related to traffic accidents that may help:
Police: They can specify the number of police cars required in each area.
Car insurance company: They can increase premiums in the hotspot area
NHS: How many ambulances are needed?
### Project Contents
Importing Data.
Data Exploration.
Data Cleaning.
Data Analysis.
Modeling Data.
## Data Loading and Preprocessing:
To start the analysis we will load the data from the UK government website www.data.gov.uk as the police forces collected the data of accidents.
which consists of two files the data about (Accidents -Vehicles) from 2005-2015, the data is separated based on timestamp so will concatenate them into one dataset. We will follow that with assessment of any necessary preprocessing, transformation or cleaning.
So we support a document to All the data variables are coded rather than textual strings.
Every column of the dataset has been represented by a numerical format.
<img src=images/Hospital-Ward-image-2.jpg width="875" height="500">
The first dataset, 1,6M records, contains information about date, time,day of the week, accident severity, location, weather, road type ...
The second dataset  Vehicles: CSV file, 3M records Contains information about vehicle type, driver age, driver sex ,.... 
then I Merge the datasets together
