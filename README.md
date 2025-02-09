# README
This Capstone Project was conducted to analyze the dataset on TLC Trip Record which is a dataset containing 
Trip Records from a taxi company called Taxi and Limousine Commissions (TLC) from January 1, 2023 to January 31, 2023.

# What I Did In Analysis?
The New York City Taxi and Limousine Commission (TLC), created in 1971, is the agency responsible for licensing and regulating New York City's Medallion (Yellow) taxi cabs, for-hire vehicles (community-based liveries, black cars and luxury limousines), commuter vans, and paratransit vehicles.
The Commission's Board consists of nine members, eight of whom are unsalaried Commissioners. The salaried Chair/ Commissioner presides over regularly scheduled public commission meetings and is the head of the agency, which maintains a staff of approximately 600 TLC employees.

The thing that I do in the analysis is to found some insight that I can see from the dataset and transform it into Data Visualizations so it can be easily to understand because humans are visual creatures.

# Problems
- Peak times of demand for taxi services
- Distribution of trip duration
- Customer trip patterns
- Distribution of the number of passengers per trip
- Main factors that influence the total fare amount

# Objective 
The Objective of the Analysis that I do in this project are to provide recommendations in the form of strategies for TLC in optimizing taxi services. 

# How to Do?
1.	What is the pattern of average trip duration?
2.	Are there seasonal patterns that influence daily income and number of trips?
3.  When is the peak time of day for taxi service demand?
4.  What are the main factors that influence the total cost of a trip?
5.  How is the distribution of the number of passengers per trip?
6. What are the daily, weekly and seasonal taxi demand trends?
7. What is the revenue pattern of taxi services, and what factors influence it?

# Dataset
This is the dataset before data cleaning
![Screenshot_16](https://github.com/user-attachments/assets/8a838f13-09c9-43f0-8264-d2262e16681a)
![Screenshot_17](https://github.com/user-attachments/assets/bb1c8ace-7547-4e87-a288-013c23003542)

These are the steps that I do for data cleaning:
1. Remove The Duplication from the dataset
2. Remove the row with NaN in several columns
3. Remove the row that cannot be changed in date time format
4. Converted the date time format to pandas date time
5. Fill the missing numbers with 0
6. Converted the category column to data type category
7. Check the outliers and remove them if there are some outliers that unacceptable
8. Drop unnecessary columns
   
This is the dataset after data cleaning
![Screenshot_23](https://github.com/user-attachments/assets/ed227f34-45ac-439c-880d-7772a0a79cd6)
![Screenshot_24](https://github.com/user-attachments/assets/0ed82c86-69ba-412e-a658-e6a288c5c818)



# Glossary
![Screenshot_21](https://github.com/user-attachments/assets/c7622752-336c-4f08-aac1-ec94ec6bea29)
![Screenshot_22](https://github.com/user-attachments/assets/600ef177-bdf2-4aa9-9b96-2645f796c729)

# Analysis

Based on the problem statement that already made, below are the analysis for the problem:
- Peak Demand Hours
- Trip Duration Distribution
- Daily Revenue Patterns
- Passenger Count per Trip
- Factors Influencing Total Fare Amount
  
And there is also optional analysis that I made and maybe can be used for the problem:
- Top 10 Pick-Up Zones
- Top 10 Drop-Off Zones
- Top Payment

# Results

Below are the result from the analysis that already conducted:
- High Demand of Taxi Services occured at 14.00 - 18.00
- The Distribution of Trip Duration somehow below 30 minutes only
- Daily Revenue Patterns show fluctuations
- Passenger Count per trip somehow mostly only 1 passenger per taxi
- The Factors that influencing for the total fare amount are fare_amount and tip_amount
- Pickup and Drop Off Zones are mnosly in LocationID no 74 and 75

  

# Conclusions and Recommendations
- Increase the Resources at the peak hours
- Develop Services for Short Duration Trips
- Promotions on Low Demand Days to Increase Daily Revenue
- Consider Ride-Sharing Services
- Development of Demand Prediction System Based on Previous Data

Thank You































