# Capstone-Starbucks-Project

## Project Overview :
This Dataset contains data provided by Starbucks for the Udacity Data science nanodegreee.We will analyise the data that being provided by looking at thetype of offers customers receive and the offers being setn out by Starbucks. Here we will analyze data provided by Starbucks through the Data Science Udacity Program. Pretty much everyone has or at least knows of the Starbucks app, and here we have data that mimic customer behavior on this app. Every now and then Starbucks will send out special offers to users on the app depending on certain circumstances. However, some customers might receive all the offers while others receive one or none.



## Problem Statement :
The goal of this project is to solve and analyze what is the best way to get the most amount of user interaction and which groups will respond to certain offers and how to present them. To help us solve this problem we will be exploring and visualizing data and viewing the results in chart visualization for people to better understand.

## Installations
This project was written in Python, using Jupyter Notebook on Anaconda. The relevant Python packages for this project are as follows:

- pandas
- numpy
- math
- json
- matplotlib
- seaborn 

## File Descriptions
This repo contains 4 files. 
- `Starbucks_Capstone_notebook.ipynb` : the code notebook .
-  `Capstone-Project-Report.pdf` : my project report .
-   `Data` :
   - profile.json
        Rewards program users (17000 users x 5 fields)
        gender: (categorical) M, F, O, or null
        age: (numeric) missing value encoded as 118
        id: (string/hash)
        became_member_on: (date) format YYYYMMDD
        income: (numeric)

   -portfolio.json
        Offers sent during 30-day test period (10 offers x 6 fields)
        reward: (numeric) money awarded for the amount spent
        channels: (list) web, email, mobile, social
        difficulty: (numeric) money required to be spent to receive reward
        duration: (numeric) time for offer to be open, in days
        offer_type: (string) bogo, discount, informational
        id: (string/hash)

   - transcript.json (https://www.kaggle.com/datasets/blacktile/starbucks-app-customer-reward-program-data?resource=download)
        Event log (306648 events x 4 fields)
        person: (string/hash)
        event: (string) offer received, offer viewed, transaction, offer completed
        value: (dictionary) different values depending on event type
        offer id: (string/hash) not associated with any "transaction"
        amount: (numeric) money spent in "transaction"
        reward: (numeric) money gained from "offer completed"
        time: (numeric) hours after start of test.
 
You can read a more descriptive article that goes into more detail [here](https://medium.com/@stephanie30024/starbucks-analysis-capstone-project-a0b0a9cdc1d9)

## Licensing, Authors, Acknowledgements .
Data for coding project was provided by Udacity.
