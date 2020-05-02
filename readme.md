# Project: Communicate Data Findings (Baywheels tripdata)
### _by Samrat Devkota_

## Introduction
This project has two parts that demonstrate the importance and value of data visualization techniques in the data analysis process.

This is the first part, here I will use Python visualization libraries to systematically __explore__ a `Baywheels tripdata` dataset, starting from plots of single variables and building up to plots of multiple variables.

In the second part, I will produce a short presentation that illustrates interesting properties, trends, and relationships that you discovered in your selected dataset.(Provided in another file)


## Dataset

[Bay Wheels](https://www.lyft.com/bikes/bay-wheels) (previously known as Ford GoBike) is a regional public bike sharing system in San Francisco Bay Area, California. Bay Wheels is the first regional and large-scale bicycle sharing system deployed in California and on the West Coast of the United States with nearly 500,000 rides since the launch in 2017 and had about 10,000 annual subscribers as of January 2018. The dataset used for this exploratory analysis consists of Bay Wheels's trip data for public use for March 2020, which you can find [here](https://www.lyft.com/bikes/bay-wheels/system-data).


## Getting started
You need an installation of Python, plus the following libraries:

* numpy
* pandas
* matplotlib.pyplot
* seaborn

## Motivation
After exploratory data analysis using visual tools in Python, I was curious about how the data changes by hours and weekdays for different user types and different access methods, which helped me to put research questions.

## Research questions and key findings

**Q1: How does the average trip duration vary during a week between customers and subscribers?**

Trip duration for customers is larger than for subscribers. Also, it is clear that subscribers spend less time in a trip than customers. Both of the user types have an increasing trend for the average time for a trip by the end of a week.

**Q2: How does the average trip duration vary during a week between different access methods?**

Overall, users accessed by the app tend to spend more time in a trip. Also, it is clear that the trend for both accessing methods is increasing by the end of a week.

**Q3: How does the hourly usage vary during a week for customers and subscribers?**

It is interesting, that customers tend to use the bike service mostly on Sunday from 12 PM to 4 PM, while subscribers will likely have a trip from Monday to Friday during rush hours (7-9 AM, 4 PM - 6 PM).

**Q4: How does the hourly usage vary during a week for app and cleaper access methods?**

The access method does not have a significant influence on a day and time of usage the service. However, if we get more data on clipper access method, the pattern may change. As it was shown before, there is a lack of data on clipper usage type, which can be associated with some technical specifications/conditions of the service.

From the bivariate and univariate data exploration I found the following interesting facts about the service:
* People tend to ride a bike less than an hour
* About 50% of trips have a duration between 6 to 14 mins.
