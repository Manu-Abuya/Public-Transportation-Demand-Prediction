# Public-Transportation-Demand-Prediction

## Project Description
The public transportation demand prediction dataset comprises information about tickets purchased from Mobiticket for 14 routes from “up country” into Nairobi for 7 months.

#### Project tasks
  1. Find the top 7 most travelled routes for a Sunday on average, indicate the average of each and rank them in decreasing order
  2. What is the probability that a passenger travelling from Kijauri will take a Shuttle if they depart before 07:30?
  3. The Sequence ‘MK’ appears in a payment reference. Based on the distribution of characters in all the payment references what do you think is the            most probable next character (if any)?
  
#### Summary
Steps performed to complete the project:
   1. Load the train_revised.csv file into a Pandas DataFrame.
   2. Preprocess the data by handling missing values and converting relevant columns to the appropriate data type.
   3. Analyze the data to answer each of the questions:
      - Group the data by route and day of the week, and compute the average number of tickets purchased for each route on Sundays. Sort the routes by the         average number of tickets purchased in decreasing order.
      - Group the data by route and departure time, and compute the probability of taking a Shuttle for each departure time. Filter the data to only               include records for departures before 07:30 from Kijauri.
      - Extract all payment references that contain the sequence "MK", and count the frequency of each character that follows "MK". The most probable next         character is the one that appears most frequently.
