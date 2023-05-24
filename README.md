# nosql-challenge

# Overview
In this challenge, we created and analyzed a MongoDB database to learn information about various establishments in the UK for a food magazine. We:
- Created a database in MongoDB from a json file.
- Updated the database to include a new restaurant.
- Cleaned the data in certain fields.
- Deleted data that was not relevant to the magazine.

# Exploratory Analysis
Once the database was cleaned, we used it to answer some of our editors' questions.
1. Which establishments have a hygiene score equal to 20?
    - There are 41 establishments with a hygiene score of 20, including "The Chase Rest Home" and "Seaford Pizza". 
2. Which establishments in London have a Rating greater than or equal to 4?
    - There are 33 establishments in London that meet this criteria. This includes "Charlie's", "Benfleet Motor Yacht Club", and "Tilbury Seafarers Centre".
3. What are the top 5 establishments with a rating of 5, nearest to the new restaurant?
    - The top 5 establishments are:
        - Volunteer
        - Plumstead Manor Nursery
        - Iceland
        - TIWA N TIWA African Restaurant Ltd.
        - Howe and Co Fish and Chips - Van 17
4. How many establishments in each Local Authority area have a hygiene score of 0?
    - Of the 55 Local Authorities included in the dataset, the 5 with the highest number of establishments with a hygiene score of 0 are:
        - Thanet - 1130
        - Greenwich - 882
        - Maidstone - 713
        - Newham - 711
        - Swale - 686