# Flight-Delay-Analysis-Dashboard
Airline Flight Delay Analytics using PowerBI

Field of interest:
Airline Industry

Problem Statement:
Flight delays are quite frequent (24% of the domestic flights arrive more than 15 minutes late) and are a major source of frustration and cost for the passengers, and there is an interest in providing this information to travelers. Flight prediction is crucial during the decision-making process for all players of commercial aviation. Moreover, the development of accurate prediction models for flight delays became cumbersome due to the complexity of air transportation system, the number of methods for prediction, and the deluge of flight data. Based on data, we would like to analyze what are the major cause for flight delays and assign a probability on whether a particular flight will be delayed.

Dataset: 
Airline delays and cancellation dataset, available on Kaggle.
(https://www.kaggle.com/yuanyuwendymu/airline-delay-and-cancellation-data-2009-2018)

Objective:
The objective of the project is to perform analysis of the historic flight data to gain valuable insights and build a predictive model to predict whether a flight will be delayed or not given a set of flight characteristics. 

The objective of the predictive model is to build a model to predict whether a flight will be delayed or not based on certain characteristics of the flight. Such a model may help both passengers as well as airline companies to predict future delays and minimize them

Goal:
To provide summary of airline delay and cancellation data to help for potential customers. Option to further drill down some airline by applying filter on airline or by year. Following are some objectives:

*Stats on total flights, their on-time, diverted, cancelled, delayed, weekdays and weekends delay count, best day to fly, day when flight is most delayed and cancelled.
*Total delays by airlines and destinations (by Map) with number of flights per airline.
*Delay by weather and airport with the reasons for delay.
*Correlation between flights and delay.
*With some airline specific like worst airport to fly with average of delay and cancel.
*Average of delay per months and more.

Data Processing And Evaluation:
*Used Power BI DAX (Power BI Query Tool) and created measures over fact data. We have:
*Attribute Subset Selection, prioritizing attributes that are essential or for making composite attribute and discarding rest of them.
*Normalize data by handled outliers, empty and negative values.
*Handled mixed value and made them uniform, like time formats in standard format for dept. time, arrival time etc.
*Calculated Average of arrival, departure, NAS, Taxi Out, weather, carrier and security delays using measures.
*Evaluated Cancellation reason out of cancellation code and cancelled bit collectively.
*Calculated weekend, start of month, day of week, day name, month name, year out of consolidated Flight date.

Outcome Dashboard:
![image](https://user-images.githubusercontent.com/21281540/230768377-4e875801-25fb-4c98-a3f2-493957d546bf.png)


